
# Problemas resueltos en clase con Diagramas de Flujo de Datos
## Ejercicio 1.- Escribir un algoritmo que escriba tu nombre.
### ANÁLISIS
Datos de entrada: ninguno\
Datos de salida: "Helios"
### DFD
![1_DFD](https://user-images.githubusercontent.com/113320901/190879911-ee710743-ffdb-4c81-8faa-babe677abc52.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| Helios |


## Ejercicio 2.- Escribir un algoritmo que escriba la fecha.
### ANÁLISIS
Datos de entrada: ninguno\
Datos de salida: "Lunes 8 de agosto"
### DFD
![2_DFD](https://user-images.githubusercontent.com/113320901/190880050-96009799-c18b-45d6-816f-f9f8cf764f61.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| Lunes 8 de agosto |


## Ejercicio 3.- Escribir un algoritmo que escriba tu nombre usando una variable.
### ANÁLISIS
Datos de entrada: ninguno\
Variables: nom\
Datos de salida: nom
### DFD
![3_DFD](https://user-images.githubusercontent.com/113320901/190880248-1a5b3def-1eff-4f84-ac5d-87a8019e5077.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| Helios |


## Ejercicio 4.- Escribir un algoritmo que escriba "Hola *-nombre-*".
### ANÁLISIS
Datos de entrada: ninguno\
Variables: nom\
Datos de salida: "Hola", nom
### DFD
![4_DFD](https://user-images.githubusercontent.com/113320901/190880334-f1b03449-5166-4da9-ac47-3259f9ccf5ad.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| Hola Helios |
  
  
## Ejercicio 5.- Escribir un algoritmo donde se le pregunte al usuario su nombre y decirle "Buen día *-nombre-*".
### ANÁLISIS
Datos de entrada: nom\
Variables: nom\
Datos de salida: "Buen día", nom
### DFD
![5_DFD](https://user-images.githubusercontent.com/113320901/190880423-5e0bc63a-1b86-4175-a8ea-c0b294708437.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| Buen día *-nom-* |
 

## Ejercicio 6.- Escribir un DFD que calcule el cuadrado de 2.
### ANÁLISIS
Datos de entrada: ninguno\
Datos de salida: 2*2
### DFD
![6_DFD](https://user-images.githubusercontent.com/113320901/190881056-0b30616d-023a-4dfb-8bca-2aba18496c8b.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| 4 |


## Ejercicio 7.- Escribir un DFD que calcule el cuadrado de *n*, para *n=5*.
### ANÁLISIS
Datos de entrada: ninguno\
Variables: n\
Datos de salida: n*n
### DFD
![7_DFD](https://user-images.githubusercontent.com/113320901/190881132-8895d18b-17f6-4d1d-b7d9-7c72eea98637.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| 25 |


## Ejercicio 8.- Escribir un DFD que pregunte al usuario el valor de *n* y obtenga su cuadrado.
### ANÁLISIS
Datos de entrada: n\
Variables: n, n1\
Datos de salida: n1 (el cuadrado del número capturado por el usuario
### DFD
![8_DFD](https://user-images.githubusercontent.com/113320901/190881383-bb9a2956-aeb4-4110-b9e7-7b2df35ae83a.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| n1 (el cuadrado del número capturado por el usuario |

| Número de caso | n | n1=n*n |
| ----------- | ----------- |----------- |
| 1 | 2 | 4=2*2|
| 2 | 3 | 9=3*3 |
| 3 | 4 | 16=4*4 |


## Ejercicio 9.- Escribir un DFD que pregunte al usuario su año de nacimiento para calcular su edad.
### ANÁLISIS
Datos de entrada: n\
Variables: n\
Datos de salida: "Tienes", n
### DFD
![9_DFD](https://user-images.githubusercontent.com/113320901/190881705-59b259bd-3be2-4634-ae37-0252a0365815.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| Tienes *n* (edad sacada del dato capturado por el usuario y una operación matemática)|

| Número de caso | n | 2022-n |
| ----------- | ----------- |----------- |
| 1 | 1997 | 2022-1997=25|
| 2 | 2007 | 2022-2007=15 |
| 3 | 2007 | 2022-2017=05 |

## Ejercicio 10.- Escribir un DFD que pregunte al usuario el año actual y su año de nacimiento para calcular su edad.
### ANÁLISIS
Datos de entrada: an_actual, an_naci\
Variables: an_actual, an_naci, edad\
Datos de salida: "Tienes esta edad:", edad
### DFD
![10_DFD](https://user-images.githubusercontent.com/113320901/190881906-b12a9b3d-b4c1-488b-89c4-fecc310c70d3.png)
### PRUEBA DE ESCRITORIO
| Salida de Datos|
| ----------- |
| Tienes esta edad:*edad*  |

| Número de caso | an_actual | an_naci | edad=an_actual-an_naci |
| ----------- | ----------- | ----------- | ----------- |
| 1 | 2022 | 2000 | 22=2022-2000 |
| 2 | 2022 | 2010 | 12=2022-2010 |
| 3 | 2022 | 2020 | 2=2022-2020 |


## Ejercicio 11.- Escribir un DFD que obtenga el cuadrado de la suma de dos números enteros.
### ANÁLISIS
Datos de entrada: n1, n2\
Variables: n1, n2, n3\
Datos de salida: n3
### DFD
![11_DFD](https://user-images.githubusercontent.com/113320901/190917330-5d3043f4-6256-427d-8245-6b3990c3b594.png)
### PRUEBA DE ESCRITORIO
| Número de caso | n1 | n2 | n3=(n2+n1)^2 |
| ----------- | ----------- | ----------- | ----------- |
| 1 | 1 | 1 | 4=(1+1)^2 |
| 2 | 2 | 3 | 25=(3+2)^2 |
| 3 | 6 | 4 | 100=(4+6)^2 |


## Ejercicio 12.- Hacer un DFD que calcule la edad con el año de nacimiento. Que no admita el número cero ni que el año actual sea mayor a 2022.
### ANÁLISIS
Datos de entrada: ano_actual, nacimiento\
Variables: ano_actual, nacimiento, edad\
Datos de salida: "Tienes ", edad, " años"
### DFD
![12_DFD](https://user-images.githubusercontent.com/113320901/190917835-e3c12805-53e5-4e71-be0f-28096600013c.png)
### PRUEBA DE ESCRITORIO
| Número de caso | ano_actual | nacimiento | edad=ano_actual-nacimiento |
| ----------- | ----------- | ----------- | ----------- |
| 1 | 0 | - | - |
| 2 | 2022 | 2023 | - |
| 3 | 2022 | 1946 | 76=2022-1946 |
| 4 | 2022 | 1992 | 30=2022-1992  |
| 5 | 2018 | 1992 | 26=2018-1992 |


## Ejercicio 13.- Escribir un DFD que imprima del número 1 al 10.
### ANÁLISIS
Datos de entrada: ninguno\
Variables: contador\
Datos de salida: contador
### DFD
![13_DFD](https://user-images.githubusercontent.com/113320901/190919055-c0dc2289-0087-46fb-9f2b-babf4404c65b.png)
### PRUEBA DE ESCRITORIO
| Número de caso | contador | contador<=10 | contador++ |
| ----------- | ----------- | ----------- | ----------- |
| 1 | 1 | 1<=10 | 2 |
| 2 | 2 | 2<=10 | 3 |
| 3 | 3 | 3<=10 | 4 |
| 4 | 4 | 4<=10 | 5 |
| 5 | 5 | 5<=10 | 6 |
| 6 | 6 | 6<=10 | 7 |
| 7 | 7 | 7<=10 | 8 |
| 8 | 8 | 8<=10 | 9 |
| 9 | 9 | 9<=10 | 10 |
| 10 | 10 | 10<=10 | 11 |
| 11 | 11 | 11<=10 | - |

## Ejercicio 14.- Escribir un DFD que obtenga la suma de los números naturales entre 1 y 10.
### ANÁLISIS
Datos de entrada: ninguno\
Variables: contador, suma\
Datos de salida: suma
### DFD
![14_DFD](https://user-images.githubusercontent.com/113320901/190919836-271e0d05-36d2-41a1-b423-f3378fe7d7f5.png)
### PRUEBA DE ESCRITORIO
| Número de caso | contador | suma | suma=suma+contador | contador<=10 | contador=contador+1 |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| 1 | 1 | 0 | 1=0+1 | 1<=10 | 2 |
| 2 | 2 | 1 | 3=1+2 | 2<=10 | 3 |
| 3 | 3 | 3 | 6=3+3 | 3<=10 | 4 |
| 4 | 4 | 6 | 10=6+4 | 4<=10 | 5 |
| 5 | 5 | 10 | 15=10+5 | 5<=10 | 6 |
| 6 | 6 | 15 | 21=15+6 | 6<=10 | 7 |
| 7 | 7 | 21 | 28=21+7 | 7<=10 | 8 |
| 8 | 8 | 28 | 36=28+8 | 8<=10 | 9 |
| 9 | 9 | 36 | 45=36+9 | 9<=10 | 10 |
| 10 | 10 | 45 | 55=45+10 | 10<=10 | 11 |  
| 11 | 11 | 55 | 66=55+11 | 11<=10 | - |  


## Ejercicio 15.- Escribir un DFD que imprima los números pares entre 1 y 10.
### ANÁLISIS
Datos de entrada: ninguno\
Variables: contador\
Datos de salida: contador*2
### DFD
![15_DFD](https://user-images.githubusercontent.com/113320901/190923518-c4d91cab-13bb-466b-8277-f34a7fdbb0db.png)
### PRUEBA DE ESCRITORIO
| Número de caso | contador | contador*2 | contador<5 | contador++ |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| 1 | 1 | 1*2 | 1<5 | 2 | 
| 2 | 2 | 2*2 | 2<5 | 3 | 
| 3 | 3 | 3*2 | 3<5 | 4 | 
| 4 | 4 | 4*2 | 4<5 | 5 | 
| 5 | 5 | 5*2 | 5<5 | - |  


## Ejercicio 16.- Escribir un DFD que diga si un número entero positivo capturado es par o impar.
### ANÁLISIS
Datos de entrada: num\
Variables: num\
Datos de salida: "Es impar" ó "Es par"
### DFD
![16_DFD](https://user-images.githubusercontent.com/113320901/190924346-b8c138dc-e618-45a4-8c68-ebca461c6880.png)
### PRUEBA DE ESCRITORIO
| Número de caso | num | num>0 | num%2==0 | impar | par |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| 1 | 1 | 1>0 | 1%2==0 | sí | no | 
| 2 | 2 | 2>0 | 2%2==0 | no | sí |
| 3 | 3 | 3>0 | 3%2==0 | sí | no |
| 4 | 4 | 4>0 | 4%2==0 | no | sí |
| 5 | 5 | 5>0 | 5%2==0 | sí | no | 
| 6 | 0 | 0>0 | - | - | - |
