## Gonzalez_Alvaro_PJ
import random 
numero_aleatorio = random.randint(0,99)

numero = int(input("Escoge número entre 0 y 99:"))

while (numero < 0) or (numero > 99):
    print("Este número no vale")

i = 1 
 while True:
    if numero_aleatorio < numero:
        print("Te pasaste!!!")
    elif numero_aleatorio > numero:
        print("Te quedaste corto, prueba otra vez")
    elif numero_aleatorio == numero:
        print("LO HAS CLAVADOOOO!!!!")
        print("Lo has acertado en",i,"intentos")
        break 
i = i+1 
