# Aula 19/08/2025

while True:
    a = int(input('Número: '))
    numero = int(input('Número: '))
    # while deixa em loop
    while a < numero:
        print(a)
        a += 1
    else:
        print('Chegou no', numero)

    continuar = input('continuar (s/n): ') .lower() .strip()
    if continuar not in ('s','sim'): 
            break
# continue = continua o que estiver presente no while      
# break encerra o loop do while
