numeros = input()
impares = []
for i in range(1, len(numeros),2):
  impares.append(int(numeros[i]))
pares = []
for a in range(0, len(numeros),2):
  if 2*int(a)<10:
    pares.append(2*int(numeros[a]))
  else:
    pares.append(2*int(a)-9)
soma = sum(pares) + sum(impares)
if int(soma/10) == soma/10:
  print("cartão válido")
else:
  print("Cartão Inválido")
