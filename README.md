# Taller-computaci-n-cient-fica-1

# saludos
import random

nombre=input("cual es tu nombre")

mensajes=["Bienvenido humano","Bienvenido terricola","Porque deberia de responder?"]

aleatorio=random.choice(mensajes)

print(aleatorio)

# multiplicación 
n=float(input("ingrese numero"))
k=float(input("ingrese numero"))
j=float(n*k)
print(j)

# vocales
n=input("ingrese palabra")
vocales=0
for letra in n:
	if letra in ("aeiou"):
		vocales +=1
print(vocales)

# piramide
n= int(input("ingrese numero"))
for i in range(1,n+1):
	for k in range(1,i+1):
		print(i,end=" ")
	print(" ")

 # adivina
 import random

x=random.randrange(1,10)

control=0
intentos=1	
while(control==0):
	print("numero de intento: ",intentos)
	print("ingrese un numero")
	n=int(input())
	if n==x:
		print("adivinaste")
		print("win")
		print("utilizaste",intentos,"intentos")
		control=1
	elif(n>x):
		print("el numero ingresado es mayor","intenta nuevamente")
		intentos +=1
	elif(n<x):	
		print("el numero ingresado es menor","intenta nuevamente")
		intentos +=1
  
# par o impar 
n=int(input("ingrese numero"))
print(n)
if n%2==0:
	print("es par") 
else:
		print("es impar")
