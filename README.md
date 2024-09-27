1,2,3 # variable for your name 
paterno = input("Ingresa tu apellido paterno paterno: ")# muestra que el usario ingresa las variable y desplegar
materno = input("Ingresa tu apellido paterno materno: ")# muestra que el usario ingresa las variable y desplegar
nombre = input("Ingresa tu nombre: ")# muestra que el usario ingresa las variable y desplegar
numero_ctrl = input("Ingresa los ultimos 4 digitos de numero de control :")# muestra que el usario ingresa las variable y desplegar
grupo = input("Ingresa tu grupo: ")# muestra que el usario ingresa las variable y desplegar

# Ejercico 1: Desplegar cada una de las variables
print("Apellido paterno: ", paterno)# muestra que que ingreso mi apellido
print("Apellido materno: ", materno)# muestra que ingreso mi materno
print("Apellido nombre : ", nombre)# muestra que ingreso mi nombre 

# Ejercicio 2: Concatenar y desplegar empezando por el apellido paterno
nombre_completo = f"{paterno} {materno} {numero_ctrl} {grupo}" #muestra que de nombre etc de todas mis datos
print("Nombre completo concatendo:", nombre_completo)# aqui igual pero diferente

# Ejercicio 3: Covertir a mayuculas y desplegar
nombre_completo_mayusculas= nombre_completo.upper()# aqui creo que covertir las mayuculas o desplegar 
print("Nomvbre completo en mayusculas:", nombre_completo_mayusculas))# aqui creo que covertir las mayuculas o desplegar 
![image](https://github.com/user-attachments/assets/39677f06-7285-45d6-a5de-653b3b68e3b2)


4# Algoritmo para leer tres valores y determinar el mayor y el menor

# 1. leer los tres valores y almacenarlos en las variables A, B, C
A = int(input("Introduce el valor de A: "))# muestra el introcion de el valor de A
B =  int(input("Introduce el valor de B: "))# MUETSRA EL INTROCION DE L VALOR de B
C = int(input("Introduce el valor de C: "))# muestra el introcion de el valor de C

# 2.Verificar si los valores son distintos
if A == B or A == C or B == C:
    print("¡Error! Los valores deben ser distintos. ")# muestra que va a sacar si son valor distintps
else:
    # 3. Desterminar el mayor y el mnor de los tres valores
    # Suponemos que A es tanto el mayor como el menor inicialmente
    mayor = A
    menor = A
    # Comparar A con B y C para encontar el mayor y el menor
if B > mayor:
        mayor = B
if C > mayor:
    mayor = C
if B < menor:
    menor = B 
if C < menor:
    menor = C

# 4. Imprimir el mayor y el menor
print("El mayor de los tres valores es:", mayor)
print("El menor de los tres valores:", menor)    
![image](https://github.com/user-attachments/assets/945a740f-e449-4159-8d7c-660b324f7c42)

5# capturamos dos valores desde el teclado 
valor1 = float(input("Introduce el primer valor: "))
valor2 = float(input("Introduce el segundo valor: "))

# Determinamos cual es el menor 
if valor1 < valor2: 
    print(f"El menor valor es: {valor1}")
elif valor2 < valor1: 
    print(f"El menor valor es:{valor2}")
else:
    print("Ambos valores son iguales")
    ![image](https://github.com/user-attachments/assets/76f22caa-ac3b-4e56-b1b2-68b979bbf7f3)

5.2 # Capturamos dos números a sumar
num1 = float(input("Introduce el primer número: "))# ingresa  numero
num2 = float(input("Introduce el segundo número: "))# ingresa numero

# Sumamos ambos números
suma = num1 + num2

# Mostramos el resultado
print(f"La suma de {num1} y {num2} es: {suma}")# muestra resultado de los valores
    ![image](https://github.com/user-attachments/assets/15d3356a-ad73-44a4-9ca6-3a6fdd0e52ad)

6 # Capturamos la base y la altura del rectángulo
base = float(input("Introduce la base del rectángulo: "))# muestra que sacar la base de area
altura = float(input("Introduce la altura del rectángulo: "))# muestra que sacar la base de area

# Calculamos el área y el perímetro
area = base * altura
perimetro = 2 * (base + altura)

# Mostramos el área y el perímetro
print(f"El área del rectángulo es: {area}")# muestra que el area saca el rectangulo es tal tal
print(f"El perímetro del rectángulo es: {perimetro}")# muestra que el area saca el rectangulo es tal tal
    ![image](https://github.com/user-attachments/assets/6d4d4345-f6b4-49d9-9574-b04cf2a5bf70)

7 # Capturamos un número natural
numero = int(input("Introduce un número natural: "))# muestra el ingresa un valor

# Verificamos si está dentro del rango 1 a 12
if 1 <= numero <= 12:
    print(f"El número {numero} está dentro de la primera docena de números naturales.")# ingresa que le pimera docena de numero 
else:
    print(f"El número {numero} no está dentro de la primera docena de números naturales.")(f"El número {numero} está dentro de la primera docena de números naturales.")# ingresa que le pimera docena de numero 
    ![image](https://github.com/user-attachments/assets/c8fe2f73-a567-4787-b9a4-70323d3a274c)

8 # Ingresar un número natural por teclado
numero = int(input("Ingrese un número natural: "))# Muestra un mensaje en la consola pidiendo al usuario que ingrese un número

# Verificar si es par o impar
if numero % 2 == 0:# 
    print(f"El número {numero} es par.")# Muestra el texto en la consola. El uso de la f antes de las comillas permite insertar el valor de la variable numero dentro del texto.
else:# Si la condición del if no se cumple (el número no es par), se ejecuta el bloque de código dentro del else
    print(f"El número {numero} es impar.")# Muestra que el número es impar si la condición del if no se cumplió.
    ![image](https://github.com/user-attachments/assets/a381ea58-ed9e-4886-aa39-20eccc79e561)


9 # Ingresar un número entero por teclado
numero = int(input("Ingrese un número entero: "))# lo convierte de texto a entero, guardando el valor en la variable numero.

# Verificar si es divisible por 7 y mayor a 40
if numero % 7 == 0 and numero > 40:
    print(f"El número {numero} es divisible por 7 y es mayor a 40.")# Si ambas condiciones se cumplen, muestra este mensaje en la consola.

else# las dos condiciones no se cumple (o el número no es divisible por 7 o no es mayor a 40), se ejecuta el bloque de código dentro del else.
    print(f"El número {numero} no cumple con ambas condiciones (divisible por 7 y mayor a 40).")# Muestra este mensaje si las condiciones no se cumplen.
![image](https://github.com/user-attachments/assets/88db779f-1eae-437b-946c-0ed7c2d21db8)


10 # Ingresar un número entero por teclado
n = int(input("Ingrese un número entero: "))# Pide al usuario que ingrese un número entero y lo convierte en un valor numérico almacenado en la variable n.

# Calcular el factorial
factorial = 1
for i in range(1, n + 1):
    factorial *= i

# Mostrar el resultado
print(f"El factorial de {n} es {factorial}.")# Finalmente, muestra el resultado del cálculo del factorial en la consola.
![image](https://github.com/user-attachments/assets/cf491152-4688-43a5-b01c-176a1144642a)











