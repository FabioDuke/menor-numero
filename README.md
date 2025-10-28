# menor-numero
numeros = []

for i in range(3):
    n = int(input(f"Digite o {i+1}º número: "))
    numeros.append(n)

menor = numeros[0]
for n in numeros:
    if n < menor:
        menor = n

print(f"O menor número é: {menor}")
