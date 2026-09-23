numeros = []

for contador in range(1, 6):
    numero = float(input(f"Digite o {contador}º número: "))
    numeros.append(numero)

soma = sum(numeros)
media = soma / len(numeros)
maior_valor = max(numeros)
menor_valor = min(numeros)

print(f"\nSoma dos números: {soma}")
print(f"Média dos números: {media:.2f}")
print(f"Maior valor: {maior_valor}")
print(f"Menor valor: {menor_valor}")
