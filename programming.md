# Introducción a la programación

En esta introducción vamos a realizar algunos cálculos y a aprender como se pueden utilizar las variables para las diferentes necesidades que podemos tener al momento de realizar un programa.

## Función print

Antes de iniciar con los temas mencionados es importante conocer una función básica de Python que se llama print, como su traducción lo indica, esta nos permite imprimir variables, cálculos o lo que necesitemos para mostrar resultados dentro del programa.
La función se utiliza poniendo la palabra print seguida de un paréntesis que abre y cierra:

```python
print()
```
Por ejemplo, digamos a nuestro programa que imprima un Hola mundo!:

```python
print("¡Hola mundo!")
```
> ¡Hola mundo!

Es importante notar en el código anterior que el texto está entre comillas, esto se debe realizar cada vez que se va a imprimir un texto.

## Aritmética

También dentro del *print( )* se pueden imprimir resultados de operaciones aritméticas como lo son las sumas, restas, multiplicaciones y divisiones. Es importante tener presente que estas operaciones no irían dentro de comillas.

```python
print(2+3)
```
> 5

O por ejemplo, una división:
```python
print(10/4)
```
> 2.5

A continuación puedes ver una tabla dónde se muestran las diferentes operaciones aritméticas:
| Operación    | Simbolo | Ejemplo      |
|----------------|--------|--------------|
| Suma       | +      | 1   + 2 = 3  |
| Resta    | -      | 5   - 4 = 1  |
| Multiplicación | *      | 2   * 4 = 8  |
| División       | /      | 6   / 3 = 2  |
| Potenciación       | **     | 3   ** 2 = 9 |

También se pueden realizar multiples operaciones simultaneamente y mediante el uso de parentésis se puede definir el orden de realización de las operaciones:
```python
print(((1 + 3) * (9 - 2) / 2) ** 2)
```
> 196.0

## Variables

Hasta el momento solamente hemos realizado calculos y los hemos imprimido, sin dejar el resultado almacenado en ningún lugar, las variables son las que nos permiten almacenar esto para hacer uso de los resultados en un futuro.

### Creación de variables

En el siguiente código podemos ver como es la creación y asignación de variables, que consite en dar un nombre y todo lo que está después del símbolo igual será lo que quede almacenado en la variable.

```python
#Asignación de valor a una variable
variable_prueba = 5 + 4

#Impresión de valor almacenado en variable
print(variable_prueba)
```
> 9

Si pudiste notar, en el código sobre cada línea de de código hay un comentario, esto se puede realizar poniendo antes de lo que se quiera comentar el símbolo #, esto le dice al sistema que no debe realizar ningún cálculo con la información a continuación.

#### Reglas para nombres de variables

Las variables tienen unas características que deben cumplir y son las siguientes:
- No pueden tener espacios
- Solamente pueden tener letras, números y guion bajo (e.g. *var_prueba!* no es un nombre válido)
- Deben iniciar con una letra (e.g. *1var_prueba* no es válido)

### Manipulación de variables
Los valores de las variables no son inmutables y pueden ser modificados cuándo sea necesario, en el siguiente código podemos ver cómo modificar el valor de una variable de 1 a 10:
```python
#Asignación de valor 1 a la variable
variable_prueba = 1

#Impresión de valor almacenado en variable
print(variable_prueba)

#Cambio de valor a la variable por 10
variable_prueba = 10

#Impresión de valor almacenado en variable
print(variable_prueba)
```
> 1
> 
> 10

También es posible realizar operaciones sobre una variable, usando el valor anterior almacenado, de la siguiente manera:
```python
#Asignación de valor a una variable
variable_prueba = 10

#Operación con variable y valor almacenado
variable_prueba = variable_prueba + 10


#Impresión de valor almacenado en variable
print(variable_prueba)
```
> 20

También es posible realizar calculos con diferentes variables, esto resulta útil cuándo una operación tiene diferentes entradas de información y es una operación compleja. En un ejemplo simplificado, a continuación queremos calcular cuántas minutos tiene un año:

```python
#Asignación de variables
dias = 365
horas_dia = 24
minutos_hora = 60

#Cálculo en nueva variable
minutos_totales = dias * horas_dia * minutos_hora

#Impresión de resultados
print(minutos_totales)
```
> 525600

## Tipos de datos

A continuación vamos a conocer los principales tipos de datos que son utilizados y para esto vamos a crear variables. Adicionalmente vamos a utilizar otra función de utilidad de *python* que nos permite saber el tipo de datos que está almacenado sobre una variable:
```python
type()
```
### Enteros (Integers)
Los números enteros son los que no tienen ningún tipo de fracción, pueden ser positivos, negativos o cero. A continuación creamos una variables con un valor entero e imprimimos el tipo de dato:
```python
x = 5
print(x)
print(type(x))
```
> 5
>
> <class 'int'>

### Punto flotante (Float)



