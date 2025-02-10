# ¿Como se representan los datos en un computador?

Los datos en un computador se representan en codigo binario, es decir, 0 y 1, lo que se conoce como bits.
La información se codifica en patrones de bits, donde cada patrón representa carácter específico. Los números se representan en binario puro, para letras se usa el codigo ASCII y para las imagenes se almacena el codigo binario en una matriz donde cada píxel tiene valores para cada color en RGB.

# ¿Cuántos estados diferentes pueden ser representados por N variables binarias?

Los estados pueden ser representados por las cantidades de variables binarias, por lo que dependen de $2^N$.

# ¿Cuáles son las unidades de almacenamiento de datos que se utilizan en computación? 


| Unidad | Equivalencia | simbolo |
|--------|-----------------------|---------|
| Byte   | 8 bits   | b |
|Kylobite| 1024 bytes   | Kb   |
|Megabyte| 1024 Kb | MB|
|Gigabyte| 1024 MB| GB|
|Terabyte| 1024 GB| TB|
|Petabyte| 1024 TB| PB|
|Exabyte| 1024 PB| EB|
|Zetabyte| 1024 EB| ZB|
|Yottabite| 1024 ZB| YB|
|Brontobite| 1024 YB| BB|
Geopbyte| 1024 BB| GB|

# ¿Cuál fue la importancia del trabajo de George Bool?

George Boole creó un sistema matemático, el álgebra booleana, que nos permite expresar y operar con ideas lógicas. Este sistema es fundamental para que las computadoras entiendan y trabajen con información en forma de ceros y unos. La lógica booleana se basa en valores de verdad (verdadero o falso) y es crucial para que las computadoras tomen decisiones, funcionen los circuitos electrónicos y se pueda programar.

# Ejercicio 2

## De binario a decimales

* 1010101010 = 512+128+32+8+2 = 682

* 11111 = 1+2+4+8+16 = 31

* 10000000 = 128

* 100100100 = 4+32+256 = 292

* 111000 = 8+16+32 = 56
 
 ## De decimales a binario

 * 127 = 64+32+16+8+4+2+1 = 1111111

* 246 = 128+64+32+16+4+2 = 11110110

* 1025 = 1024+1 = 10000000001

* 354 = 256+64+32+2 = 101100010

* 187 = 128+32+16+8+2+1 = 10111011

# Ejercicio 3

## Tipos de datos:

* Entero: Son números sin decimales, como -3, 0 o 42. Sirven para contar elementos, realizar operaciones aritméticas y muchas otras tareas.

* Flotantes: números que contienen decimales, como -3.14, 0.0 o 42.5. Los flotantes permiten representar fracciones y valores más precisos que los enteros.

* String: Las cadenas de texto son secuencias de caracteres, como «Hola o «12345». Se utilizan para almacenar y manipular texto.

* Booleano: Los booleanos son tipos de datos que solo pueden tener dos valores: verdadero (true) o falso (false). Son esenciales para la toma de decisiones en el código mediante estructuras condicionales. 

* Array: son colecciones de elementos del mismo tipo, como [1, 2, 3] o [«a», «b», «c»]. Se utilizan para almacenar listas de datos y se accede a sus elementos mediante índices. 

* Object: estructuras de datos complejas que pueden contener múltiples valores y tipos de datos. Por ejemplo, {nombre: «Juan», edad: 30} o {producto: «Laptop», precio: 1500}. 

* Null: El valor nulo representa la ausencia de un valor o una referencia vacía. Indica que una variable no tiene asignado ningún dato. 

* Undefined: El valor indefinido se utiliza para indicar que una variable fue declarada pero no se le asignó ningún valor.

# Ejercicio 4:

|Tipos de datos: |Caracteristica |C|Java|Python|
|----------------|---------------|-|-|-|
|Entero|Son números sin decimales|int|int|int|
|Entero corto|Valor entero de menor tamaño| short int| short| no existe
|Entero largo|Valor entero de mayor tamaño| long int|long|No existe|
|Flotante|números que contienen decimales|Float|Float|Float|
|Caracter|secuencias de caracteres|Char|Char|str|
|Booleano|Solo pueden ser verdadero o falso|_bool|boolean|bool|
|Array|colecciones de elementos del mismo tipo|int arr [ ]|int [ ]|list o tuple
|nulo| una variable no tiene asignado ningún dato.| Null| Null| None



