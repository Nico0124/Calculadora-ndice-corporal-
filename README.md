# Calculadora-ndice-corporal-
#La calculadora de índice corporal te permite detectar si tienes un peso saludable para tu altura 
peso = float (input ("Introduzca su peso en Kg: "))
altura = float (input ("Introduzca su altura en metros: "))

imc = peso / (altura ** 2) 

if imc < 18.5:
    Resultado = "Bajo peso"
elif imc > 25:
     Resultado = "Sobrepeso"
else:
     Resultado = "Peso Normal"

print (f"Su IMC es: {imc:.1f}. usted tiene {Resultado}.")
