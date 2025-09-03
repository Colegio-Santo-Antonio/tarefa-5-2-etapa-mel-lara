numeros = input()
impares = []
for i in range(1, len(numeros),2):
  impares.append(int(numeros[i]))
pares = []
for i in range(0, len(numeros),2):
  if 2*int(i)<10:
    pares.append(2*int(numeros[i]))
  else:
    pares.append(2*int(i)-10+1)
soma = sum(pares) + sum(impares)
if int(soma/10) == soma/10:
  print("cartão válido")
else:
  print("Cartão Inválido")
