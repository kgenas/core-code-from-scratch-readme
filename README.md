
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

	 function generateHashtag (str) {
	     let result = '#'+str.split(/\s/g).map(w => (w.charAt(0).toUpperCase()) + w.slice(1)).join('');
	     if (result === '#' || result.length >140 ) return false;

	     return result;
	 }    

String incrementer

	 function incrementString (strng) {
	    // return incrementedString
	    let result = strng.replace(/[0-9]+$/g, (num) => { 
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
<div align="center">  
  <h2>Week challenges (Wednesday):computer:</h2>
</div>

## Count strings in objects
```js
	  function strCount(obj){
	    // Your code here
		let count = 0
	    //* recorre todos los elementos(nombre de la variable) del objeto
		for (key in obj) {
		//* prueba ----> console.log( key ,' ', obj[key])
		if (typeof obj[key] == 'string') count++;
		if (typeof obj[key] == 'object') count+= strCount(obj[key]);//* llamada recursiba
	    }

	    return count
	  }
```

## Extending JavaScript Objects: Get First & Last Array Element
```js
	    Array.prototype.first = function() {
	    return this[0];
	    };

	    Array.prototype.last = function() {
	    return this[this.length-1];
	    };

```

## Object Oriented Piracy
```js
	    function Ship(draft,crew) { 
	    this.draft = draft;
	    this.crew = crew;

	    this.isWorthIt = function (){
			return (this.draft - this.crew * 1.5) > 20;
	    	}
	    }
```
<div align="center">  
  <h2>Week challenges (Thursday):computer:</h2>
</div>

## Convert a String to a Number
```js
	const stringToNumber = function(str){
	  // put your code here
	  return Number(str);
	}
```

## Convert number to reversed array of digits
```js
	function digitize(n) {
	  //code here
	  return String(n).split('').reverse().map( num => Number( num ))
	}
	
	//otra solucion
	
	const a = 3234234
	console.log( String(a).split('').reverse().map( Number) )
```

## Truthy and Falsy
```js
	const truthy = [true,{},[],42,"0","false"];
	const falsy = [false,null,undefined,0,NaN];
```

## Training JS #4: Basic data types--Array
```js
	function getLength(arr){
	    //return length of arr
	    return arr.length
	}
	function getFirst(arr){
	    //return the first element of arr
	    return arr.shift()
	}
	function getLast(arr){
	    //return the last element of arr
	    return arr.pop()
	}
	function pushElement(arr){
	    var el=1;
	    //push el to arr
	    arr.push(el)
	    return arr
	}
	function popElement(arr) {
	    //pop an element from arr
	    arr.pop()
	    return arr
	}
```
<div align="center">
  <h1>Javascript - Week 8</h1>
  <h2>Week challenges (Monday)  :computer:</h2>
</div>

## Training JS #7: if..else and ternary operator
```js
	function saleHotdogs(n){
	  if( n < 5 ) return n*100
	  else if( n >= 5 && n < 10 ) return n*95
	  else return n*90
	}
```

## Training JS #8: Conditional statement--switch
```js
	function howManydays(month){
	  var days;
	  switch (month){
	      
	      case  1:
	      case  3:
	      case  5:
	      case  7:
	      case  8:
	      case  10:
	      case  12:
		  days = 31;
		  break;
	      case  4:
	      case  6:
	      case  9:
	      case  11:
		  days = 30;
		  break;
	      default:
		  days = 28;
	  }
	  return days;
	}
```

## Basic calculator
```js
	function calculate(num1, operation, num2) {
	 //TODO: make a basic calculator. 
	  switch( operation){
	      case '+':
		 return num1 + num2;
		 break;
	      case '-':
		return num1 - num2;
		break;
	      case '*':
		return num1 * num2;
		break;
	      case '/':
		if( num2 == 0 ) return null;
		if( num1 >0 &&  num2 < 0 ) return num2;
		return num1 / num2;
		break;
	      default:
		return null
	      
	  }
	}
```
<div align="center">  
  <h2>Week challenges (Tuesday)  :computer:</h2>
</div>

## Even or odd
```js
	function evenOrOdd(number) {
	  
	  let value = number % 2 == 0 ? 'Even':'Odd';
	  return value   
	}
```

## A wolf in sheep's clothing
```js
	function warnTheSheep(queue) {

	  let count = 1;
	  if('wolf' === queue.pop()) return 'Pls go away and stop eating my sheep';
	  while ('wolf' !== queue.pop()) count++;
	  return `Oi! Sheep number ${count}! You are about to be eaten by a wolf!`;
	  
	}
```

## Decode the morse code
```js
	decodeMorse = function(morseCode){
	  // Your code here
	  // You can use MORSE_CODE[morse]
	  
	  let morse = morseCode.trim().split(' ');
	  let space = 1;
	  let message='';

	 for(let index=0; index < morse.length; index++){
	   if(morse[index] === '') space++;
	   if(morse[index] ==='' && space===3){
	     message +=' ';
	     space =1;
	   }   
	   if(MORSE_CODE[morse[index]]) message += MORSE_CODE[morse[index]];
	 }
	 return message;
	  
	}
```
<div align="center">  
  <h2>Week challenges (Wednesday):computer:</h2>
</div>

## Who likes it?
```js
	function likes(names) {
    
	    let value = '';    
	    if (names.length == 0) return 'no one likes this';
	    if (names.length == 1) return `${names.shift()} likes this`;
	    if (names.length == 2) return `${names.shift()} and ${names.shift()} like this`;
	    if (names.length == 3) return `${names.shift()}, ${names.shift()} and ${names.shift()} like this`;

	    value += `${names.shift()}, ${names.shift()}`;    
	    value += ` and ${names.length} others like this`;
	    return value;
	}
```

## Bit counting
```js
	var countBits = function(n) {
	  // Program Me  
	  return n.toString(2).split('').filter( x => x ==='1').length
	};
```

## Your order, please
```js
	function order(words){
	  // ...
	  let wordOne = words.split(' ');
	  let wordTwo = words.split('').sort().filter( x => Number(x));
	  let value ='';

	  for( let index=0; index < wordTwo.length; index++){
	    const match = new RegExp(wordTwo[index],'g');
	    value += wordOne.filter( x => x.match(match)) +' ';
	  }
	  return value.trim()
	}
```
<div align="center">  
  <h2>Week challenges (Thursday):computer:</h2>
</div>

## Counting duplicates
```js
	 function duplicateCount(text){
	    
	    let s1 = text.split('');
	    let s2 = text;
	    let count = 0;

	    for (let index = 0; index < s1.length; index++) {
		let match = new RegExp(s1[index], 'gi');        

		if (s2.match(match) !== null) {        
		    if (s2.match(match).length > 1) {
			s2 = s2.replace(match, '');
			count++;
		    }
		}


	    }
	    return count;
	}
```

## Encrypt this!
```js
	 var encryptThis = function (text) {
	    // Implement me! :)
		let letras = text.split(' ');
		for (let index = 0; index < letras.length; index++) {
		    if (letras[index].length > 3) {                        
			letras[index] = letras[index][0] + letras[index][letras[index].length - 1] + letras[index].substring(2, (letras[index].length)-1) + letras[index][1]

		    } else {
			letras[index] = letras[index][0] + letras[index].substring(1, letras[index].length).split('').reverse().join('')
		    }

		    const match = new RegExp(letras[index][0], 'i');    
		    letras[index] = letras[index].replace(match,letras[index][0].charCodeAt(0));

		}

		return letras.join(' ');
	    }
```

## Valid parentheses
```js
	 function validParentheses(parens) {
	    // your code here ..
		while (parens.includes('()')) parens = parens.replace(/\(\)/, '');        

		return parens.length == 0 
	 }
```


## Convert string to camel case
```js
	 function toCamelCase(str){
		let letter =str.split(/-|_/);
		let result = '';
		    if(letter.length ===1 ) return '';
		    for (let index = 0; index < letter.length; index++) {

			if (index !== 0) result += letter[index][0].toUpperCase() + letter[index].substring(1);
			else result += letter[index][0] + letter[index].substring(1);
		    }
		return result;
	 }
```
<div align="center">
  <h1>Javascript - Week 9</h1>
  <h2>Week challenges (Monday)  :computer:</h2>
</div>

## "this" is a problem
```js
	 function NameMe(first, last) {
		this.firstName = first;
		this.lastName = last;
		this.name = this.firstName + ' ' + this.lastName;
	 }
```

##  Thinkful - List and Loop Drills: Lists of lists
```js
	  function processData(data){
		//your code here
		let result = data.map( array => array[0] - array[1]).reduce( (add,value)=> add * value, value=1)

		return result;
	  }
```

##  Stop gninnipS My sdroW!
```js
	  function spinWords(string){
	    //TODO Have fun :)
	    let result = string.split(' ').map( value =>{
		if( value.length >= 5){
		return value.split('').reverse().join('');
		}
		return value;
	    }).join(' ')
	    return result;
	  }
```

<div align="center">  
  <h2>Week challenges (Tuesday)  :computer:</h2>
</div>


##   "this" is an other problem
```js
	function NamedOne(first, last) {
	// -- SHOULD be changed --
	    this.firstName = first;
	    this.lastName = last;    
	    Object.defineProperty(this,'fullName',{                
		    get: function(){
			return this.firstName +' '+this.lastName
		    },
		    set: function(value){
			const name = value.split(' ');    
			if( name.length == 2){
			  this.firstName = name[0];
			  this.lastName = name[1];
			}
	    }})
	}
```

##  Who likes it?"
```js
	  function likes(names) {
	    let value = '';    
	    if (names.length == 0) return 'no one likes this';
	    if (names.length == 1) return `${names.shift()} likes this`;
	    if (names.length == 2) return `${names.shift()} and ${names.shift()} like this`;
	    if (names.length == 3) return `${names.shift()}, ${names.shift()} and ${names.shift()} like this`;

	    value += `${names.shift()}, ${names.shift()}`;    
	    value += ` and ${names.length} others like this`;
	    return value;
	 }
```

##  Convert string to camel case
```js
	  function toCamelCase(str) {
		  let letter =str.split(/-|_/);
		  let result = '';
		    if(letter.length ===1 ) return '';
		    for (let index = 0; index < letter.length; index++) {

			if (index !== 0) result += letter[index][0].toUpperCase() + letter[index].substring(1);
			else result += letter[index][0] + letter[index].substring(1);
		    }
		  return result;
	}
```

<div align="center">  
  <h2>Week challenges (Wednesday)  :computer:</h2>
</div>

##  Easy mathematical callback
```js
	function processArray(arr, callback) {
 	   return arr.map(callback);
	}
```

##  Moving Zeros To The End
```js
	function processArray(arr, callback) {
 	   return arr.map(callback);
	}
```

##  Valid Parentheses
```js
	function validParentheses(parens) {
	  // your code here ..
	  while (parens.includes('()')) parens = parens.replace(/\(\)/, '');                
	  return parens.length == 0 
	}
```

<div align="center">  
  <h2>Week challenges (Thursday)  :computer:</h2>
</div>

##  The Hashtag Generator
```js
	 function generateHashtag (str) {
	     let result = '#'+str.split(/\s/g).map(w => (w.charAt(0).toUpperCase()) + w.slice(1)).join('');
	     if (result === '#' || result.length >140 ) return false;

	     return result;
	 }    
```

##  String incrementer
```js
	 function incrementString (strng) {
	    // return incrementedString
	    let result = strng.replace(/[0-9]+$/g, (num) => { 
		let newNum = (parseInt(num) + 1).toString();
		while (newNum.length < num.length) {
		    newNum = "0" + newNum;
		}
		return newNum;
	    })
	    if( result === strng) return result.concat(1) 
	    return result
	 }    
```
<div align="center">
  <h1>Javascript - Week 10</h1>  
</div>

## Week challenges

<div align="center">
  <h1>React - Week 11</h1>  
</div>

## Week challenges 

<div align="center">
  <h1>Node.JS - Week 12 12</h1>  
  <h2>Week challenges (Monday)  :computer:</h2>
</div>

## Node.JS Core Understanding

### 1. What is Node.JS?
 >  Node.js® es un tiempo de ejecución de JavaScript 
    basado en el motor de JavaScript V8 de Chrome

 #### What is NPM?
 > Administrador de paquetes de nodos

### 2. What problem does Node.JS solve (Is there any problem that can be solved with Node.JS thinking)?
 > Trata de resolver problemas en la parte del BackEnd
 
### 3. What is the V8 Javascript Engine?
 >  El motor de JavaScript es quien convierte tu codigo de JavaScript en
    codigo ejecutable por la maquina en la que va a correr.

### 4. Is Node.JS really necessary in the Development ecosystem?
 > Es necesario y es una opcion mas la ventaje que tiene que se basa en
   JavaScript la cual se puede usar el mismo lenguaje en fronEnd que
   backEnd
 
 #### Why not use PHP or Golang?
  >  Es otra alternativa de poder usar el backEnd, va depender de las necesidades
     del negocio cual usar.

### 5. What is the difference between Node.JS and any other browser?
 >  Tanto el navegador como Node.js utilizan JavaScript como lenguaje
    de programacion. La creacion de aplicaciones que se ejecutan en el 
    navegador es algo completamente diferente a la creacion de una aplicacion
    Node.js
 #### Are Node.JS and a browser the same?
  >  En el navegador, la mayoría de las veces lo que está haciendo es interactuar con
     el DOM u otras API de la plataforma web como las cookies. Esos no existen en
     Node.js, por supuesto. No tiene el documenty window todos los demás objetos que
     proporciona el navegador.
 
### 6. What is NVM and Why is it useful for Node.JS developers?
 > npm es el administrador de paquetes estandar para Node.js

  #### npm
   >  gestiona las descargas de las dependencias de tu proyecto
      administra el control de versiones, por lo que puede especificar
      cualquier version especifica de un paquete o solicitar una version
      superior o inferior a la que necesita
 
## Node.JS Module System

### 1. What is a Javascript Module?
 >  Los programas JavaScript comenzaron siendo bastante pequenos
    la mayor parte de su uso en los primeros dias era para realizar
    tareas de scripting aisladas, proporcionando un poco de interactividad
    a tus paginas web donde fuera necesario, por lo que generalmente no se
    necesitaban grandes scripts. Avancemos unos anos y ahora tenemos
    aplicaciones completas que se ejecutan en navegadores con mucho
    JavaScript, JavaSript ahora se usa en otros contextos( Node.js )

### 2. Why are Javascript Modules necessary?
 > Crea módulos para organizar y estructurar mejor su base de código. 
   Puede usarlos para dividir programas grandes en fragmentos de 
   código más pequeños, más manejables y más independientes que llevan 
   a cabo una o varias tareas relacionadas.

### 3. What module standards are available in Node.JS?
 > Los módulos ECMAScript son el formato estándar oficial para empaquetar código 
   JavaScript para su reutilización. Los módulos se definen usando una variedad 
   de declaraciones import y export.

### 4. What are the differences between ESModules and CommonJS modules?
 > No __filename o __dirname
   >> Estas variables de CommonJS no están disponibles en los módulos ES.

 > No NODE_PATH    		
  >> NODE_PATH no es parte de import los especificadores de resolución. 
     Utilice enlaces simbólicos si desea este comportamiento.

### 5. Which types of modules exist in Node.JS?
 > Node.js tiene dos sistemas de módulos: módulos CommonJS y módulos ECMAScript.

## Node.JS Hello World - Practice

### 1. Why do we run the npm init command and not node init to create a new Node.JS project?
 > npm init
   Genera el archivo package.json
			
### 2. When you entered the npm init command and answered the questions you saw in the terminal, a new file called packacke.json was generated.
```js   
   package.json: contiene
	{
	  "name": "hello_world_node",
	  "version": "1.0.0",
	  "description": "",
	  "main": "index.js",
	  "scripts": {
	    "test": "echo \"Error: no test specified\" && exit 1"
	  },
	  "author": "",
	  "license": "ISC"
	}
```
### What does this file do?	
 > Su finalidad es mantener un historial de los paquetes instalados y optimizar 
   la forma en que se generan las dependencias del proyecto y los contenidos de 
   la carpeta node_modules/
	
### Why is this file generated?
  > - el archivo contiene  la semántica de la versión que tiene el proyecto
  > - versión: versión del proyecto
  > - description: que lo que resuelve el proyecto y porque fue creado
  > - entry point: indica donde inicia el archivo a ejecutar el proyecto
  > - git repository: el cual donde está el repositorio de git
  > - keywords: palabras claves para encontrar nuestro proyecto
  > - author: el creador del proyecto
  > - license: licencia de software

## Node.JS Module System - Practice

### operations.js
```js	 
	const sum = (x , y) => {
	    return x + y
	}
	
	const subtract = ( x , y) => {
	    return x - y
	}
	
	module.exports = { sum, subtract }
```
### main.js
```js	
	const { sum, subtract } = require('./operations');
	
	let value01 = 4;
	let value02 = 4;
	
	let total = 0;
	
	total = sum(value01,value02);
	console.log(`sum: ${total}`)
	
	total = subtract(value01,value02);
	console.log( `substract: ${total}` )
```
<div align="center">  
  <h2>Week challenges (Wednesday)  :computer:</h2>
</div>

## Client-Server Model

### 1. What is a Server?
 > Los servidores son computadoras orientadas al alojamiento y despacho
   de datos de distinto tipo.

### 2. What is a Client?
 > Un cliente puede solicitar código de programa actualizado o el uso de 
   aplicaciones de un servidor de código. Para obtener un nombre o una 
   dirección, un cliente se pone en contacto con un servidor de nombres. 
   Un cliente también puede solicitar archivos y datos para la 
   entrada de datos, las consultas o la actualización de registros de un 
   servidor de archivos.

### 3. Is a server just another physical computer?
 > No

 #### 3.1 Why do we refer to a certain class of applications as Servers?
  > por que se realiza peticiones y se obtiene  información según lo
    solicitado

 #### 3.2 What is the difference?
  > La manera que se realiza la comunicación y el tipo de información
    que provee

### 4. Is there any similarity between human communication and the client-server model?
   > humanos
     - uno pregunta otro responde

   > maquina
     - una maquina manda una solicitud y otra maquina despacha 
   
   #### 4.1 List some examples
   > - alumo pregunta a maestro
   > - compra en linea o mercado
 
## 5. Is the client-server model applicable only to the Web?
   > No

   #### 5.1 Do desktop applications use the client-server model?
   > Si
 
   #### 5.2 Can you mention any other example of this model outside the Web?
   > - Servidores Windows
   > - Servidores Unix
   > - Servidor de Base de Datos


## HTTP Learning Exercise

### 1. What is HTTP?
 > Es un protocolo de la capa de aplicacion 
   para la transmision de documentos hipermedia, como HTML.

### 2. What is a Communication Protocol?
 > Los protocolos de comunicaciones pueden cubrir la autenticación, 
   la detección y corrección de errores y la señalización. También 
   pueden describir la sintaxis, la semántica y la sincronización 
   de las comunicaciones analógicas y digitales.

 #### 2.1 Do humans use communication protocols?
  > Si

### 3. What is a Request in HTTP?
 > HTTP define un conjunto de métodos de petición para indicar la 
   acción que se desea realizar para un recurso determinado.

### 4. What is a Response in HTTP?
 > Los códigos de estado de respuesta HTTP indican si se ha
   completado satisfactoriamente una solicitud HTTP específica.

### 5. What is an HTTP method?
 > Existen varios tipos de métodos de solicitud HTTP, que modifican 
   por completo el tipo de respuesta que obtiene del servidor. 
   Los más comunes son:

   >> - GET
   >> - HEAD
   >> - POST
   >> - PUT
   >> - DELETE
   >> - CONNECT
   >> - OPTIONS
   >> - TRACE 
   >> - PATH

### 6. What are HTTP request headers?
 > Los encabezados de solicitud vienen justo después de las líneas de 
   solicitud y brindan información adicional sobre la transacción. 
   El encabezado especifica información sobre el host, el software 
   del servidor web que utiliza el cliente final, cuál es el agente 
   de usuario del cliente y más.

## APIs Core Understanding


### 1. What is an API?
 > Un software intermediario que permite que las aplicaciones se 
   comuniquen entre sí. Cada vez que se usa una aplicación como Facebook, 
   se envía un mensaje instantáneo o se mira el pronóstico del tiempo en 
   el teléfono, se utiliza una API.

### 2. What is a Protocol?
 > Los protocolos de comunicaciones pueden cubrir la autenticación, 
   la detección y corrección de errores y la señalización. También 
   pueden describir la sintaxis, la semántica y la sincronización 
   de las comunicaciones analógicas y digitales.

### 3. Is the term API only applicable to the communication of programs over the Internet?
 > No, en los inicios de API era una comunicacion local

### 4. Why is structured communication between two programs important?
 > Facilidad de crear soluciones mas robustas, cada programa soluciona algo
   muy especifico y por lo tanto la integracion de los programas se puede
   generar una solucion compleja

4.1 Do we humans use APIs when communicating without technology?
 > Si, por ejemplo se realiza una solicitud de un plato al mesero
   el mesero traslada nuestro pedido al chef.

5. Is an API just another program or a standard?
 > Es un programa donde se realiza peticiones especificas por ejemplo el clima.
   Nota: los sistemas REST interactúan a través de operaciones estándar en los
   recursos, no dependen de la implementación de interfaces.

6. Do you know any API? Can you list at least 5 examples of APIs?
 >- API Google Maps
 >- Star Wars API
 >- New York Times Movie Reviews
 >- Call of Duty: Modern Warfare
 >- Lord of the Rings API

## From JSON to REST


### 1. What is JSON?
 > un formato basado en texto estándar para representar datos 
   estructurados en la sintaxis de objetos de JavaScript. Es comúnmente 
   utilizado para transmitir datos en aplicaciones web

#### 1.1 Is JSON the same as a plain Javascript object?
 > JSON es un formato de texto que es completamente independiente del lenguaje 
   pero utiliza convenciones que son familiares para los programadores de la 
   familia de lenguajes C, incluidos C, C++, C#, Java, JavaScript, Perl, Python 
   y muchos

### 2. What is REST?
 > REST es una interfaz para conectar varios sistemas basados en el protocolo 
   HTTP (uno de los protocolos más antiguos) y nos sirve para obtener y generar
   datos y operaciones, devolviendo esos datos en formatos muy específicos, 
   como XML y JSON.

#### 2.1 Is REST a programming language, framework, technology, or architecture pattern?
 > architecture pattern

### 3. What is a Resource in REST?
 > recursos en un sistema REST    			
 >- GET: recupera un recurso específico (por id) o una colección de recursos
 >- POST: crea un nuevo recurso
 >- PUT: actualiza un recurso específico (por id)
 >- ELIMINAR: eliminar un recurso específico por id.

3.1 What is a resource identifier?
 > Forma que queremos interactuar con un sistema o la accion que se desea

### 4. How are HTTP and REST related?
 > REST usa el Protocolo HTTP para la transmicion de datos

#### 4.1 What HTTP methods does REST use within its architecture rules?
 > REST se apoya en HTTP, los verbos que utiliza son exactamente los 
   mismos, con ellos se puede hacer GET, POST, PUT y DELETE.

#### 4.2 Why do we use HTTP methods in REST and how do they relate to resources?
 > Los metodos de HTTP y REST son las mismas accione entre los dos,
   al usar un metodo tiene el mismo fin para ambos solamente que cada uno lo
   trabaja a su manera.

### 5. Is REST the same as HTTP?
 >- REST es una arquitectura
 >- HTTP es un protocolo de comunicacion

## REST API Clients
