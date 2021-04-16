# H1
def imc(estatura, peso):
    return peso / estatura**2

estatura = float(input("Ingrese estatura en mt: "))
peso = float(input("Ingrese peso en kg: "))

indice = imc(estatura, peso)

print("Tu índice de masa corporal es:") 
print(round(indice, 2))
