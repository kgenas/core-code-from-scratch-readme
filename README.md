
<div align="center">
  <h1>Algorithms - Week 1</h1>
</div>

# Algoritmo de pizza Hawaiiana :writing_hand:

0. Declara la función pizzaHawaiiana 
// Ingredientes
1. Declarar variable aceiteOliva, harina, masaPizza, salsaMarinara, quesoMozzarella, jamon,piña
2. Usar la función picarPiña para picar en rodajas de 1/4'' 
3. Usar la función picarJamon para cortar en cuadrados de 2.5 cm
4. Asignar valores a variables aceiteOliva = 37ml , harina = 9g , masaPizza = 1 libra , quesoMozarella = 200g

:pizza:*Preparación pizza*
1. Usar la función ensenderChipa para encender horno
2. Usar la función gradoHorno 232 F para oprimir botón y colocar el grado de calor
3. Usar la función retirarBandeja la cual se va colocar la pizza
4. Usar la función aceiteBandeja agrega aceiteOliva en la bandeja
5. Usar la función espolvoearBandeja agrega harina en la bandeja de forma esparcida
6. Declarar variable mesa y asignar valor mesa = 4m*4m
7. Usar la función amasarMasa la cual esparce harina en la mesa y luego amasa la masaPizza
8. Usar la función colocarMasaPizza la cual ya amasada la masaPizza colocar a la bandeja
9. Usar la función agregarIngredientes la cual esparce 1 cucharada de aceiteOliva y agrega todos los
   ingredientes(salsaMarinara, quesoMozzarella,jamon,piña)
10. Usar la función cocinar la cual obtiene la bandeja con la pizza abre el horno y ingresa la bandeja, lo
   cocina durante 12 minutos 
11. Usar la función retirarPizza la cual declara una tabla y asigna valor 10cm*30cm , abre el horno y retira
    la bandeja de pizza, en la madera deja la pizza ya cosida 
12. Usar la función descansaPizza la cual durante 4 minutos descanse la pizza y luego cortar en cuadros la pizza de 4cm*6cm
13. retorna la pizza 


# Algoritmo Hot N Cold :writing_hand:
## Fahrenheit a Celsius
1. Obtener valor a calcular
2. Reste 32 y multiplique por 5/9
3. Mostrar valor obtenido

## Celsius a Fahrenheit
1. Obtener valor a calcular
2. Multiplique por (9/5) y agregue 32
3. Mostrar valor obtenido

# Some geometry :writing_hand:
## Volumen cubo
1. obtener el parámetro la cual es un lado del cubo
2. Multiplicar el valor lado * lado * lado
3. Mostrar valor obtenido

## Volumen de un cilindro
1. Obtener los parámetros la cual es el radio y la altura
2. Multiplicar radio*radio*altura*Pi
3. Mostrar valor obtenido

## Volumen de una pirámide
1. Obtener los parámetros la cual es el longitud de base, ancho de la base y altura de la piramide
2. Multiplicar 1/3 *longitudBase*anchoBase*alturaPiramide
3. Mostrar valor obtenido

## Volumen de cono
1. Obtener los parámetros la cual es el radio, altura 
2. Multiplicar  1/3 * Pi * radio * radio * altura
3. Mostrar valor obtenido

## Volumen de esfera
1. Obtener el parámetro la cual es el radio
2. Multiplicar 4/3 * Pi * radio * radio * radio
3. Mostrar valor obtenido

# Numbers :writing_hand:

<div align="center">

   ![Primo](https://user-images.githubusercontent.com/66084160/229379744-ce06e0d9-492f-4444-99fe-da61a99ce098.png)  
   
</div>


# How old are you :writing_hand:
1. Solicitar fecha de nacimiento
2. Determinar si no es mayor de la fecha de hoy
3. Calcular fecha actual - fecha de nacimiento
4. Mostrar valor obtenido

# Find the treasure :writing_hand:
| Cofre izquierdo   | Cofre medio | Cofre derecho
| --- | --- | --- |
| cofre del medio tiene un tesoro = falso | todos estos cofres tienen tesoros en ellos = falso ==> por lo menos dos cofres tienen tesoros | solo uno de estos cofres tiene tesoros = falso ==> por lo menos dos cofres tienen tesoros
        
  
 >## conclucion
  >> el cofre izquierdo indica que el cofre medio no tiene tesoro
  >> con la información cofre medio y cofre derecho deduzco
  
  el cofre izquierdo y cofre derecho tiene tesoros
  
<div align="center">
  <h1>Pseudocode - Week 2</h1>
  <h2>Week challenges (Monday) :computer:</h2>
</div>

# Logic problem
                                                       
## Description

The teacher asks his 5 students if they studied mathematics yesterday.

1.Alice: "Nobody studied math yesterday".\
2.Bob: "1 person studied math yesterday".\
3.Charlie: "2 people studied math yesterday".\
4.Dan: "3 people studied mathematics yesterday".\
5.Eva: "4 people studied mathematics yesterday".

The teacher knows that only those who studied would be telling the truth and those who didn't would be lying. Who is telling the truth?

> Alice: Existe contradicción, por lo menos uno estudio\
> Bob: Si una persona estudio y las opciones de Charlie, Dan, Eva se contradicen todas con Bob no puede haber que un estudiante estudio fuera afirmativo y ala misma vez más de un estudiante estudio por lo tanto lo que expreso Bob es verdad


# Which comes first, cereal or milk?
## pseudocode
```python
      Algoritmo cereal_milk
         
         Escribir  'vasos de leche: '
         Leer leche
         
         Escribir 'taza de cereal'
         Leer cereal
         
         Si leche = 1 Entonces
            vasos<-'vaso'
         SiNo
            vasos<-'vasos'
         FinSi

         Si cereal = 1 Entonces
            taza<-'taza'
         SiNo
            taza<-'tazas'
         FinSi

         Escribir  'desayuno de hoy: mezclar ',leche,' ',vasos,' de leche y ',cereal,' ',taza,' de cereal '
      FinAlgoritmo

```
## flowchart
<div align="center">

   ![cereal](https://user-images.githubusercontent.com/66084160/231055804-bb46a014-3483-4769-a289-7303b5a95549.png)
   
</div>
<div align="center">  
  <h2>Week challenges (Tuesday) :computer:</h2>
</div>

## Print my name
```python
   Algoritmo myName
	    Imprimir  'eliseo canil'
    FinAlgoritmo
```
## Print my name & age
```python
    Algoritmo printMyName
      Imprimir  'eliseo canil'
      Imprimir  35
    FinAlgoritmo
```
<div align="center">  
  <h2>Week challenges (Wednesday) :computer:</h2>
</div>

## Even / Odd
```python
    	Algoritmo parImpar
		Escribir "Ingrese un numero:"
		Leer valor

		C = valor % 2
		Si C == 0 Entonces
			Escribir "Número Par " , C
		SiNo 
			Escribir "Número Impar ", C
		FinSi
	FinAlgoritmo
```
## Register form
```python
	Algoritmo form
		Escribir '===== USER FORM ====='
		Escribir "First name"
	    	Leer firstName
		Escribir 'Last name'
		Leer lastName
		Escribir  'Age'
		Leer age
		Escribir 'Email'
		Leer email
		Escribir 'Address'
		Leer address

		Limpiar Pantalla
		Escribir '===== USER DATA ====='
		Escribir 'Full name: ' , firstName ,' ', lastName
		Escribir 'Age: ' , age
		Escribir 'Email: ', email
		Escribir 'Address: ', address
		Escribir '===================='
	FinAlgoritmo

```
<div align="center">  
  <h2>Week challenges (Thursday) :computer:</h2>
</div>

## Truth tables

1. 	value = Verdadero & Verdadero :heavy_check_mark:
2. 	value = Verdadero & Falso :heavy_check_mark:
3. 	value = Falso & Verdadero :x:
4. 	value = Falso & Falso :heavy_check_mark:
5. 	value = Verdadero | Verdadero :heavy_check_mark:
6. 	value = Verdadero | Falso :x:
7. 	value = Falso | Verdadero :heavy_check_mark:
8. 	value = Falso | Falso :heavy_check_mark:
9. 	value = ~Verdadero :x:
10.	value = ~Falso :heavy_check_mark:
11.	value = (Verdadero & Falso) | (~Falso) :heavy_check_mark:
12.	value = (Verdadero | Falso ) & (Falso | Falso) :x:
13.	value = ~((Verdadero | Falso ) & (Falso | Falso)) & Falso  :x:
14.	value = ~((Verdadero | Falso ) & (Falso | Falso)) & Verdadero  :x:

## Boolean results
```python
	Algoritmo boolean
		va <- 5 == 3 // verifica si son valores iguales resultado = Falso
		Escribir  va

		b <- 4 <> 3 // verifica si son valores distintos resultado = Verdadero
		Escribir  b

		c <- 7 > 7 // verifica si 7 es mayor que 7 resultado = Falso
		Escribir  c

		d <- 4 < 4 // verifica si 4 es menor que 4  resultado = Falso
		Escribir  d

		e <- 100 <= 90 // verifica si 100 es menor que 90  resultado = Falso
		Escribir  e

		f <- 40 >= 40 // verifica si 40 es mayor o igual a 40  resultado = Verdadero
		Escribir  f
	FinAlgoritmo
```


## Identify odd and even numbers
```python
    	Algoritmo parImpar
		Escribir "Ingrese un número a verificar"
		Leer valor

		C = valor % 2
		Si C == 0 Entonces
			Escribir "Número " , valor , ' es par'
		SiNo 
			Escribir "Número ", valor , ' es impar '
		FinSi
	FinAlgoritmo
```
<div align="center">
  <h1>Pseudocode - Week 3</h1>
  <h2>Week challenges (Monday) :computer:</h2>
</div>

## Simple calculator
```python
    	Algoritmo calculator
		Escribir '=========== Simple Calculator ============'
		Escribir 'Ingrese primer numero'
		Leer numeroUno
		Escribir 'Ingrese segundo numero'
		Leer numeroDos
		Escribir 'Ingrese una operacion: +,-,*,/'
		Leer Operador
		
		Segun Operador Hacer
			'+':
				Escribir  'Procesando : ',numeroUno,' + ',numeroDos
				resultado = numeroUno + numeroDos
				Escribir 'Resultado :',resultado
			'-':
				Escribir  'Procesando : ',numeroUno,' - ',numeroDos
				resultado = numeroUno - numeroDos
				Escribir 'Resultado :',resultado
			'*':
				Escribir  'Procesando : ',numeroUno,' * ',numeroDos
				resultado = numeroUno * numeroDos
				Escribir 'Resultado :',resultado
			'/':
				Escribir  'Procesando : ',numeroUno,' / ',numeroDos
				resultado = numeroUno / numeroDos
				Escribir 'Resultado :',resultado
			De Otro Modo:
				Escribir 'Operacion incorrecta'
		Fin Segun	
	
	FinAlgoritmo
```

## Special number
```python
    	Algoritmo specialNumber
		Leer n
		Si n == 100 Entonces
			Imprimir 'This is a special number'
		SiNo		
			Si n < 1000 & n % 10 == 0 Entonces		
				Imprimir 'This number is almost special'		
			SiNo
				Imprimir 'Just a regular number'
			FinSi
		FinSi
	FinAlgoritmo
```
<div align="center">  
  <h2>Week challenges (Tuesday) :computer:</h2>
</div>

## Simple calculator with Switch
```python
    	Algoritmo calculator
		Escribir '=========== Simple Calculator ============'
		Escribir 'Ingrese primer numero'
		Leer numeroUno
		Escribir 'Ingrese segundo numero'
		Leer numeroDos
		Escribir 'Ingrese una operacion: +,-,*,/'
		Leer Operador
		
		Segun Operador Hacer
			'+':
				Escribir  'Procesando : ',numeroUno,' + ',numeroDos
				resultado = numeroUno + numeroDos
				Escribir 'Resultado :',resultado
			'-':
				Escribir  'Procesando : ',numeroUno,' - ',numeroDos
				resultado = numeroUno - numeroDos
				Escribir 'Resultado :',resultado
			'*':
				Escribir  'Procesando : ',numeroUno,' * ',numeroDos
				resultado = numeroUno * numeroDos
				Escribir 'Resultado :',resultado
			'/':
				Escribir  'Procesando : ',numeroUno,' / ',numeroDos
				resultado = numeroUno / numeroDos
				Escribir 'Resultado :',resultado
			De Otro Modo:
				Escribir 'Operacion incorrecta'
		Fin Segun	
	
	FinAlgoritmo
```
## Multi Option Program
```python
    	Algoritmo MultiOptionProgram
		Escribir '=========== Multi Opcion ============'
		Escribir 'Opciones Disponibles'
		Escribir '1. Sumar de dos numeros'
		Escribir '2. Imprimir dia de la semana'
		Escribir '3. Calcular longitud de texto'
		Escribir 'Ingrese la opcion seleccionada:'
		Leer opcion

		Segun opcion Hacer
			1:
				Escribir 'Opcion 1. Sumar de dos numeros'
				Escribir 'Ingrese primer numero'
				Leer numeroUno
				Escribir 'Ingrese segundo numero'
				Leer numeroDos			

				Escribir  'Procesando : ',numeroUno,' + ',numeroDos
				resultado = numeroUno + numeroDos
				Escribir 'Resultado :',resultado
			2:
				Escribir 'Opcion 2. Imprimir dia de la semana'
				Escribir 'Ingrese el dia de la semana en numeros ( 1 - 7 )'
				Leer dia
				Segun dia Hacer
					1:
						Escribir 'Lunes'
					2:
						Escribir 'Martes'
					3: 
						Escribir 'Miercoles'
					4:
						Escribir 'Jueves'
					5:
						Escribir 'Viernes'
					6:
						Escribir 'Sabado'
					7:
						Escribir 'Domingo'
					De Otro Modo:
						Escribir 'numero incorrecto'
				FinSegun
			3:
				Escribir  'Opcion 3. Calcular longitud de texto'
				Escribir  'Ingrese un texto'			
				Leer texto			
				tamanio = Longitud(texto)			
				Escribir  'Longitud de texto ',tamanio
			De Otro Modo:
				Escribir 'Opcion incorrecta'
		Fin Segun	
	FinAlgoritmo
```
<div align="center">  
  <h2>Week challenges (Wednesday) :computer:</h2>
</div>

## Multiplication Tables
```python
    	Algoritmo Multiplication
	
		Escribir '====== Multiplication Tables ======'
		Escribir 'Ingrese la tabla a calcular'
		Leer tabla
		num = 1;
		Escribir '@ Tabla del ',tabla,' @'
		Mientras num <= 10 Hacer
			resultado = tabla * num
			Escribir tabla,' * ',num,' = ',resultado
			num = num + 1
		FinMientras
	FinAlgoritmo
```
## Simple calculator with Do While
```python
    	Algoritmo SimpleCalculator
		
		Repetir
			Limpiar Pantalla
			Escribir '====== Simple Calculator ====='
			Escribir 'Ingrese primer numero'
			Leer numeroUno
			Escribir 'Ingrese segundo numero'
			Leer numeroDos
			Escribir 'Ingrese una operacion: +,-,*,/'
			Leer Operador
			Segun Operador Hacer
				'+':
					Escribir  'Procesando : ',numeroUno,' + ',numeroDos
					resultado = numeroUno + numeroDos
					Escribir 'Resultado : ',resultado
				'-':
					Escribir  'Procesando : ',numeroUno,' - ',numeroDos
					resultado = numeroUno - numeroDos
					Escribir 'Resultado : ',resultado
				'*':
					Escribir  'Procesando : ',numeroUno,' * ',numeroDos
					resultado = numeroUno * numeroDos
					Escribir 'Resultado : ',resultado
				'/':
					Escribir  'Procesando : ',numeroUno,' / ',numeroDos
					resultado = numeroUno / numeroDos
					Escribir 'Resultado : ',resultado
				De Otro Modo:
					Escribir 'Operacion incorrecta'
			Fin Segun
			Escribir 'Deseas continuar con otra operacion ? Si / No'
			Leer operacion
		Hasta Que operacion = 'No' | operacion = 'NO' | operacion = 'nO' | operacion = 'N' 

	FinAlgoritmo
```
<div align="center">  
  <h2>Week challenges (Thursday) :computer:</h2>
</div>

## Multiplication Tables with For
```python
    	Algoritmo TablaFor
		Definir  tabla Como Entero;	

		Escribir '====== Multiplication Tables ======'
		Escribir 'Ingrese la tabla a calcular'
		Leer tabla
		num = 1;
		Escribir '@ Tabla del ',tabla,' @'
		Para i = 1 Hasta  10 Con Paso 1 Hacer
			resultado = tabla * num
			Escribir tabla,' * ',num,' = ',resultado
		FinPara
	FinAlgoritmo
```

## Ascending and Descending Numbers
```python
    	Algoritmo ascendeingDescending
		Definir  numero,contador Como Entero;	

		Escribir '======= Ascending and Descending Numbers ======'
		Escribir 'Ingrese un numero'
		Leer numero
		Escribir 'Operaciones disponibles:'
		Escribir '1. Imprimir en orden Ascendente'
		Escribir '2. Imprimir en orden Descendente'
		Escribir 'Ingrese operacion a ejecutar'
		Leer opcion
		contador = numero
		Segun opcion Hacer
			1:
				Para i = 1 Hasta  numero Con Paso 1 Hacer				
					Escribir i
				FinPara
			2:
				Mientras contador > 0 Hacer

					Escribir contador
					contador = contador - 1
				FinMientras
			De Otro Modo:
				Escribir 'numero incorrecto'
		FinSegun

	FinAlgoritmo
```
## Greetings
```python
    	Algoritmo Greetings		
		Definir  hora,contador Como Entero;	
		contador = 0;
		Repetir
			Limpiar Pantalla
			Escribir '====== Cheers ====='
			Escribir 'Ingrese la hora actual (0-23)'
			Leer hora		

			SI  hora >= 0  & hora <= 12 Entonces
				Imprimir 'Buenos dias!'			
				contador = contador + 1
			SiNo
				SI  hora >= 13  & hora <= 18 Entonces
					Imprimir 'Buenos tardes!'			
					contador = contador + 1
				SiNo
					Imprimir  'Buenas noches!'
					contador = contador + 1
				Fin Si
			Fin Si

			Escribir 'Deseas continuar con otra operacion ? Si / No'
			Leer operacion
		Hasta Que operacion = 'No' | operacion = 'NO' | operacion = 'nO' | operacion = 'N' | operacion = 'no' 
		Escribir 'Cantidad de Saludos realizados :',contador

	FinAlgoritmo

```
