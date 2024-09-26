# variable for your name 
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


# Algoritmo para leer tres valores y determinar el mayor y el menor

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


