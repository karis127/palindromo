# palindromo

def palindromo(x):
    inverso = ''
    for i in range(len(x)-1, -1, -1):
        inverso += x[i]
    return inverso

palavra = str(input('Digite: '))
frase = palavra.split()
x = ''.join(frase)

if palindromo(x) == x:
    print('CLOSE CERTO É PALINDROMO')

else:
    print('VITTAR ESTÁ TRISTE, CLOSE ERRADO, NÃO É PALINDROMO!!!!')
