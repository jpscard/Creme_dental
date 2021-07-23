import math
#População que escova os dentes: 191.985.875,1
#crianças de 0 a 4: 13247025
#crianças de 5 a 9: 13208628
#apartir de 10 anos: 165530221
print('Considere os membros familiares e preencha:')
print('')
while True:

    a = int(input("Insira a quantidade de crianças com idade entre 0 a 4 anos: "))
    while a < 0:
        print("Quantidade inválida, insira valor maior ou igual a zero")
        a = int(input("Insira a quantidade de crianças com idade entre 0 a 4 anos: "))

    b = int(input("Insira a quantidade de crianças com idade entre 5 e 9 anos: "))
    while b < 0:
        print("Quantidade inválida, insira valor maior ou igual a zero")
        b = int(input("Insira a quantidade de crianças com idade entre 5 a 9 anos: "))

    c = int(input("Insira a quantidade de pessoas com idade a partir de 10 anos: "))
    while c < 0:
        print("Quantidade inválida, insira valor maior ou igual a zero")
        c = int(input("Insira a quantidade de pessoas com idade a partir de 10 anos: "))
    break
#valor em gramas de creme dental consumido mensalmente
a_mes = 30*(3*0.1*a)
b_mes = 30*(3*0.2*b)
c_mes = 30*(3*0.4*c)
#quantidade de tubos vendidos por mes por categoria
a_qtd = float(math.ceil(a_mes/50))
b_qtd = float(math.ceil(b_mes/50))
c_qtd = float(math.ceil(c_mes/90))
#total de tubos vendidos somada as categorias
t_qtd = a_qtd + b_qtd + c_qtd

print('')
print('Crianças de 0 a 4 anos:', a)
print('Consumo mensal em gramas:%.2f'% a_mes)
print('Quantidade de creme dental de 50g:', a_qtd)
print('_'*100)
print('Crianças de 5 a 9 anos:', b)
print('Consumo mensal em gramas:%.2f'% b_mes)
print('Quantidade de creme dental de 50g:', b_qtd)
print('_'*100)
print('Pessoas a partir de 10 anos:', c)
print('Consumo mensal em gramas:%.2f'% c_mes)
print('Quantidade de creme dental de 90g:', c_qtd)
print('-' * 45)
print('Total vendidos ao mês:', t_qtd)
