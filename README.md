numeros = input()
impares = []
for i in numeros[-1: :-2]:
  impares.append(int(i))
parres = []
for i in numeros [-2: :-2]:
  if 2*int(i)<10:
    pares.append(2*int(i))
  Else:
    pares.append(2*int(i)-10+1)
soma = sum(pares) + sum(impares)
if int(soma/10) == soma/10:
  print("cartão válido")
else:
print("Cartão Inválido")
