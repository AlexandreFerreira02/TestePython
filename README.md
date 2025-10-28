# TestePython

class Carro:
    def __init__(self):
        self.motor_ligado = True

    def ligar(self):
        if self.motor_ligado:
            print('Vrum-vrum')

class Motor:
    def __init__(self, modelo):
        self.modelo = modelo
        self.carro = Carro()

    def funcionando(self):
        print(f'{self.modelo} está ligado')
        self.carro.ligar()

c1 = Motor('Carro')
c1.funcionando()
