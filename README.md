
[Custom foo description](#flowchart)
</br>
[Custom foo description](#average-sales-and-commission)

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
<div align="center">
  <h1>Pseudocode - Week 4</h1>
  <h2>Week challenges (Monday) :computer:</h2>
</div>

## Average sales and commission
```python
    	Algoritmo avergaSales
		Definir sales,contador Como Entero;	
		Definir value,total,average, commission Como Real;	
		Escribir 'write the total number of sales to enter'
		Leer sales
		contador = 1
		total = 0;
		Mientras contador <= sales Hacer

			Escribir 'Write the value of the sale number: ', contador
			Leer value
			total = value + total
			contador = contador + 1
		FinMientras
		average = total / sales 
		Si sales >= 6 
			commission = total * 0.15
		SiNo
			commission = total * 0.10
		FinSi

		Escribir 'The average sales is: ',average
		Escribir 'The commission received by the seller is: ',commission

	FinAlgoritmo

```
## Even or odd
```python
    	Algoritmo Eve	
		Definir numero,EvenOdd Como Entero
		Repetir

			Escribir  'write a number between 1 and 50'
			Leer numero
			Si numero < 1 | numero > 50
				Escribir  'invalid number'
			FinSi		
		Hasta Que  numero >= 1 & numero <= 50

		EvenOdd = numero % 2
		contador = 1
		Si EvenOdd == 0 Entonces

			Mientras contador <= numero Hacer

				EvenOdd = contador % 2
				Si EvenOdd == 0 
					Escribir  contador
				FinSi
				contador = contador + 1
			FinMientras

		SiNo 
			Mientras contador <= numero Hacer

				EvenOdd = contador % 2
				Si EvenOdd <> 0
					Escribir  contador
				FinSi
				contador = contador + 1
			FinMientras
		FinSi

	FinAlgoritmo
```
<div align="center">  
  <h2>Week challenges (Tuesday) :computer:</h2>
</div>

## Full name
```python
    	Algoritmo fullName
		Definir name, lastName Como Caracter;
		Escribir  'write a name'
		Leer name

		Escribir 'write a last name'
		Leer lastName

		// name and lastName
		Escribir  Mayusculas(Subcadena(name,0,1)),Minusculas(Subcadena(name,2,Longitud(name))),' ',Mayusculas(Subcadena(lastName,0,1)),Minusculas(Subcadena(lastName,2,Longitud(lastName)))

	FinAlgoritmo
```

## Throw dice
```python
    	Algoritmo throwDice	
		Definir contador,diceOne,diceTwo Como Entero;
		Mientras contador < 10 Hacer

			diceOne = Aleatorio(1,7)
			diceTwo = Aleatorio(1,7)

			Si diceOne == diceTwo Entonces
				Escribir diceOne,' ',diceTwo,' ','the dice are the same'
			SiNo
				Escribir diceOne,' ',diceTwo
			Fin Si

			contador = contador + 1
		Fin Mientras
	FinAlgoritmo
```

<div align="center">  
  <h2>Week challenges (Wednesday) :computer:</h2>
</div>

## Distance to zero
```python
    	Algoritmo DistanceZero
		Definir contador,number,compear Como Real;
		contador = 1;
		compear = 0;
		Mientras contador <= 5 Hacer
			Escribir 'Write a number'
			Leer number
			Si abs(number) > abs(compear) Entonces
				compear = number
			Fin Si
			contador = contador + 1
		Fin Mientras
		Escribir  trunc(compear)
	FinAlgoritmo

```

## Toss coin
```python
    	Algoritmo TossCoin
		Definir valueOne,valueTwo, coin Como Entero;
		Definir playerOne, playerTwo Como Caracter;

		Escribir 'enter the name of the first player'
		Leer playerOne

		Escribir 'enter the amount to play'
		Leer valueOne

		Escribir 'enter the name of the second player'
		Leer playerTwo

		Escribir 'enter the amount to play'
		Leer valueTwo

		Si valueOne <= 0 & valueTwo <= 0 Entonces
			Escribir 'game canceled'
		SiNo
			Si valueOne <= 0 & valueTwo > 0 Entonces			
				Escribir 'player wins: ',Mayusculas(playerTwo)
			FinSi

			Si valueOne > 0 & valueTwo <= 0 Entonces
				Escribir 'player wins: ',Mayusculas(playerOne)
			FinSi

			Si valueOne > 0 & valueTwo > 0 Entonces
				coin = aleatorio(1,2)

				Si coin == 1 Entonces
					Escribir 'player wins: ',Mayusculas(playerOne),' amount won: ',valueTwo
				SiNo
					Escribir 'player wins: ',Mayusculas(playerTwo),' amount won: ',valueOne
				Fin Si
			FinSi
		Fin Si
	FinAlgoritmo

```
<div align="center">  
  <h2>Week challenges (Thursday) :computer:</h2>
</div>

## Total price
```python
    	Funcion value <- TotalPrice ( price, vat )
		Definir value Como Real
		Si  price > 3000 Entonces
			value = ( price + ( price / 100 * vat ) ) / 100*90
		SiNo
			value = ( price + ( price / 100 * vat ) )
		Fin Si
	Fin Funcion

	Algoritmo CallTotalPrice

		Imprimir  'precio 100 vat 20 ', TotalPrice(100,20)
		Imprimir  'precio 10000 vat 25 ', TotalPrice(10000,25)
		Imprimir  'precio 5000 vat 21 ', TotalPrice(5000,21)
	FinAlgoritmo

```

## Reverse direction and size
```python
    	Funcion palabra <- Reverse ( letras )	
		Definir tamanio Como Entero
		Definir letra, palabra Como Caracter

		tamanio = Longitud(letras)	
		Mientras tamanio > 0 Hacer

			letra = Subcadena(letras,tamanio,tamanio)		
			Si  letra == Minusculas(letra)  Entonces
				palabra = palabra + Mayusculas(letra)
			SiNo
				palabra = palabra + Minusculas(letra)
			Fin Si
			tamanio = tamanio - 1		
		Fin Mientras

	Fin Funcion

	Algoritmo reverseDirection

		Imprimir  Reverse('Text HelLo')
		Imprimir  Reverse('HelLO')
		Imprimir  Reverse('Leonardo')
		Imprimir  Reverse('Text')
	FinAlgoritmo


```
<div align="center">
  <h1>Pseudocode - Week 5</h1>
  <h2>Week challenges (Monday) :computer:</h2>
</div>

## Time Converter
```python
    	Funcion convertir <- timeConverter ( calcular )
		Definir days, hours, minutes,seconds Como Entero
		Definir convertir Como Caracter
		days = trunc( calcular / 86400 )
		hours =trunc(( calcular % 86400 ) / ( 60*60 ))
		minutes = trunc((( calcular % 86400 ) % ( 60*60 ))/ 60)
		seconds = (( calcular % 86400 ) % ( 60*60 )) % 60

		convertir = 'days: ' + ConvertirATexto(days) + ' hours: ' + ConvertirATexto(hours) + ' minutes: ' + ConvertirATexto(minutes) + ' seconds: ' + ConvertirATexto(seconds)

	Fin Funcion

	Algoritmo Convert
		Imprimir timeConverter(4000)
		Imprimir timeConverter(400)
		Imprimir timeConverter(150000)
	FinAlgoritmo

```
## Compare distances
```python
    	Funcion trueFalse <- CompareDistances ()

		Definir count Como Entero
		Definir value,total Como Real
		count = 1
		total = 0
		Mientras count <= 5 Hacer
			Escribir 'Write a number'
			Leer value		
			total = total + value		
			count = count + 1		
		Fin Mientras
		trueFalse = total > 0

	Fin Funcion

	Algoritmo Compare
			Imprimir  CompareDistances()
	FinAlgoritmo
```
<div align="center">  
  <h2>Week challenges (Tuesday) :computer:</h2>
</div>

## Sum of pairs
```python
    	Funcion add <- SumPairs ()
		Definir number Como Real

		add = 0
		Repetir		
			Escribir  'write a number between 1 and 100'
			Leer number
			Si number > 0 & number < 101 Entonces
				SI number % 2 == 0 Entonces
					add = add + number 	
				FinSi			
			FinSi		
		Hasta Que  number < 1 | number > 100

	Fin Funcion

	Algoritmo Sum
		Imprimir  SumPairs()
	FinAlgoritmo
```
## Mid point
```python
    	Funcion number <- between ( numberOne , numberTwo )

		Definir total, number Como Real	
		total = numberOne + numberTwo		
		number = total / 2 

	Fin Funcion

	Algoritmo MidPoint

		Escribir  between( 40,80)	// 60
		Escribir  between( 40,-80)	// -20
		Escribir  between( 50,50)	// 50
		Escribir  between( -50,50)	// 0
		Escribir  between( 12,6)	// 9

	FinAlgoritmo

```
<div align="center">  
  <h2>Week challenges (Wednesday) :computer:</h2>
</div>

## Cashier
```python
    	Funcion total <- CallCashier ()
		Definir opcion Como Caracter
		Definir money Como Real
		total = 1000;
		Repetir		
			Escribir  ' select an option '
			Escribir ' a. to deposit '
			Escribir ' b. withdraw '
			Escribir ' c. go out '		
			Leer opcion
			Si opcion =='b' | opcion =='B'  Entonces
				Escribir 'How much do you want to withdraw'				
				Leer money
				total = total - money
			FinSi	

			Si opcion =='a' | opcion =='A'  Entonces
				Escribir 'How much do you want to deposit'				
				Leer money
				total = total + money
			FinSi	

		Hasta Que  opcion =='c' | opcion =='C'
	Fin Funcion

	Algoritmo Cashier

		Imprimir CallCashier()
	FinAlgoritmo

```
## Weather average
```python
    	Funcion average <- CallWeather()
		Definir opcion Como Caracter
		Definir count Como Entero
		Definir valor,celsius Como Real

		average = 0
		Repetir		
			Escribir  ' select an option '
			Escribir ' a. enter degrees celsius '
			Escribir ' b. enter degrees fahrenheit '
			Escribir ' c. go out '
			Leer opcion
			Si opcion =='a' | opcion =='A'  Entonces
				Leer valor
				average = average + valor			
				count = count + 1			

			FinSi	

			Si opcion =='b' | opcion =='B'  Entonces
				Leer valor			
				average = average + ( valor -32) / 1.8 
				count = count + 1

			FinSi	

		Hasta Que  opcion =='c' | opcion =='C'
		average = average / count
	Fin Funcion

	Algoritmo Weather

		Imprimir CallWeather()
	FinAlgoritmo
```
<div align="center">  
  <h2>Week challenges (Thursday) :computer:</h2>
</div>

## If
```js
	const hi = 'hi'
	if( hi === 'hi'){
	    console.log('hi, how are you')
	}else{
	    console.log('Did not say hi')
	}
```
## While
```js
	let i = 1
	while (i < 10) {
	    console.log('tabla 2 x',i,' ',i*2)
	    i++;
	  }
```

## For
```js
	  for (let i = 0; i < 10; i++) {
	    console.log('tabla 2 x',i,' ',i*2)
	  } 
```

<div align="center">
  <h1>JavaScript - Week 6</h1>
  <h2>Week challenges (Tuesday):computer:</h2>
</div>

## Variables
```js
	  let firstname = 'Lata'
```

## What is x?
```js
	 let x = 'Geeta';
	 //Which value does x have after execution of the following code? 
		'Geeta'	 
```

## Several variables
```js
	//Exercise
		//Declare a variable flower and assign it the value 'rose'. 
		//Declare a second variable tree and assign it the value 'maple'.
	let flower = 'rose'
	let tree = 'maple'	 
```

## Reassignment
```js
	//Exercise
		//Which value does x have after execution of the following code? 
	let x = 'Tic';
	x = 'Tac';
	x = 'Toe';
	
	'Toe'
```

## Assign variables
```js
	//Exercise
		//Which value does x have after execution of the following code? 
	let x = 'Laurel';
	let y = 'Hardy';
	let z = y;
	y = x;
	x = z;
	
	'Hardy'
```
<div align="center">  
  <h2>Week challenges (Wednesday):computer:</h2>
</div>

## Functions
```js
	function hello(){
	 return 'Hello world!';
	}
```

## Multiple functions
```js
	function a(){
	 return 'Hello a!'
	}

	function b(){
	 return 'Hello b!'
	}
```

## Function calls
```js
	function greet(){
	 return 'Haydo!';
	}

	let salutation = greet();
```

## What is x? (function version)
```js
	'How do you do?'
```

## Parameters
```js
	function echo(input)
	{
	 return input
	} 
```
<div align="center">  
  <h2>Week challenges (Thursday):computer:</h2>
</div>

## Strings
```js
	function greet(hello){
	 return 'Hello ' + hello +'!'
	}	 
```


## String: length
```js
	function length(text){
	 return text.length
	}		 
```

## String: toUpperCase()
```js
	function toCase(text){
	 return text.toLowerCase()+'-'+text.toUpperCase()
	}		 
```

## String: charAt()
```js
	function shortcut(textOne, textTwo){
	 return textOne.charAt(0) + textTwo.charAt(0)
	}	 
```

## String: indexOf()
```js
	function indexOfIgnoreCase(textOne, textTwo){
	  let a = textOne.toLowerCase();
	  let b = textTwo.toLowerCase();
	  return a.indexOf(b)
	}	 
```

<div align="center">
  <h1>JavaScript - Week 7</h1>
  <h2>Week challenges (Monday):computer:</h2>
</div>

## String: substr()
```js
	  function firstWord(word) {
		const position = word.indexOf(' ');
		const newWord = word.substr(0,position);
		return newWord;
	   }
```

## String: replace()
```js
	    function normalize(date)
	    {
		let newDate = date.replace(/-/g,'/')
		return  newDate
	    }
```

## Increment
```js
	     // Which value does x have after execution of the following code ? 
		let x = 3;
		x++;
		x = x * 2;
		x--;

	    // answer
		7
```

## Fahrenheit
```js
	    function toFahrenheit(Celsius){
		return Celsius * (9/5) +32 
	    }
```

## Boolean
```js
	    function nand(valueOne,valueTwo){
		let x1 = valueOne && valueTwo
		return !x1
	    }
```

<div align="center">  
  <h2>Week challenges (Tuesday):computer:</h2>
</div>

## Objects
```js
	  function animal(obj) {
	    return `This ${obj.color} ${obj.name} has ${obj.legs} legs.`;
	 }
```

## Return to sanity
```js
	  function mystery() {
		var results =
		    {sanity: 'Hello'};
		return results;
	   }
```

## Object syntax debug
```js
	  var rooms = {
	    first: {
		description: 'This is the first room',
		items: {
		chair: 'The old chair looks comfortable',
		lamp: 'This lamp looks ancient'
		}
	    },
	    second: {
		description: 'This is the second room',
		items: {
		couch: 'This couch looks like it would hurt your back',
		table: 'On the table there is an unopened bottle of water'
		}
	    }
	  }
```

