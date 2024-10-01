print('-=-' * 5, 'TABUADA', '-=-' * 5)
n = int(input('Digite um número inteiro: '))
for c in range(0, 11):
    print('{}x{} = {}'.format(n,c,(n*c)))
