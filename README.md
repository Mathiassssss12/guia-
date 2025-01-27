#codigo numeros pares 
def identificar_pares_impares(lista_numeros):
    pares = []
    impares = []

    for numero in lista_numeros:
        if numero % 2 == 0:
            pares.append(numero)
        else:
            impares.append(numero)
    
    return pares, impares

# Ejemplo de uso
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
pares, impares = identificar_pares_impares(numeros)

print("Números pares:", pares)
print("Números impares:", impares)
