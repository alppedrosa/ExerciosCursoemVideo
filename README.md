# Meu projeto

nome = input('Digite seu nome?')
print('É um prazer te conhecer,{}!'.format(nome))

n = int(input('Digite sua idade:'))
print('Analisando sua idade {}, o antencessor de sua idade é {} e o sucessor de sua idade é {}'.format(n, (n-1), (n-2)))

n = int(input('Digite novamente sua idade:'))
print('O dobro de sua idade {} é {}.'.format(n, (n*2)))
print('O tripo de sua idade {}, é {}. \ne a  raiz quadrada de sua idade {} é {:.2f}.'.format(n, (n*3), n, pow(n,(1/2))))

n1 = float(input('Sua primeira nota na escola foi:'))
n2 = float(input('Sua segunda nota na escola foi:'))
media = (n1 + n2) /2
print('Sua primeira nota{:.1f} e {:.1f} é igual a {:.1f}'.format(n1, n2, media))
print('Então vc foi aprovado na escola André!')
escola = input('Na escola vc gostava de matematica André?')
n = input('Digite a materia que gostava?')
n = input('Gostava do que em matematica?')
num = int(input('Digite qual tabuada vc gostava?'))
print('-' *12)
print('{} x {} = {}'.format(num, 1, num*1))
print('{} x {} = {}'.format(num, 2, num*2))
print('{} x {} = {}'.format(num, 3, num*3))
print('{} x {} = {}'.format(num, 4, num*4))
print('{} x {} = {}'.format(num, 5, num*5))
print('{} x {} = {}'.format(num, 6, num*6))
print('{} x {} = {}'.format(num, 7, num*7))
print('{} x {} = []'.format(num, 8, num*8))
print('{} x {} = {}'. format(num, 9, num*9))
print('{} x {} = {}'.format(num, 10, num*10))
print('-' *12)
print('Essa é a tabuada que gostava!')

salario = float(input('Qual seu salario? R$'))
novo = salario + (salario * 15 /100)
print('Com o salario de R$ {:.2f}, tendo um aumento de 15%, passara a  receber R$ {:.2f}'.format(salario, novo))
print('Parabéns pelo aumento André!')
