# Exercicio096.py

def area(larg,comp):
    a = larg * comp
    print(f'A area de um terreno{larg} x {comp} é de: {a}m²')


#Programa principal
print('Controle do terreno')
print('=-'*30)
l = float(input('Largura(m): '))
c = float(input('COMPRIMENTO(m): '))
area(l,c)
