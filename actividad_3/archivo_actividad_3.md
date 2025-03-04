#  ¿Cuáles son los símbolos que se utilizan para representar cada operación de un algorimo con un diagrama de flujo?

Los simbolos para representar las operaciones de un algoritmo con un diagrama de flujo son:

![Texto alternativo](images/11.png)
![Texto alternativo](images/12.png)
![Texto alternativo](images/13.png)
![Texto alternativo](images/14.png)

# Ejercicio 2

#### Construye un algoritmo que, al recibir como datos el ID del empleado y los seis primeros sueldos del año, calcule el ingreso total semestral y el promedio mensual, e imprima el ID del empleado, el ingreso total y el promedio mensual.
 ![Texto alternativo](images/22.png)

 # Ejercicios adicionales
 1. Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.

 ### Pseudocódigo:

 ``` 
Inicio

// Declaración de variables
Entero Lapices
Real Pago

// Entrada de datos
Leer Lapices
Leer Pago

// Condicional
Si Lapices > 1000 Entonces
    Pago = Lapices * 0.85  // Descuento del 15%
SiNo
    Pago = Lapices * 0.9   // Descuento del 10%

// Salida de resultados
Escribir Pago

Fin
 ``` 


 ![Texto alternativo](images/23.png)

 2. Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo.

### Pseudocódigo:

 ```
Inicio

// Declaración de variables
Real Compra
Real Precio_final
Real Descuento

// Entrada de datos
Leer Compra

// Condicional
Si Compra > 250000 Entonces
    Descuento = Compra * 0.15
SiNo
    Descuento = Compra * 0.08

// Cálculo del precio final
Precio_final = Compra - Descuento

// Salida de resultados
Escribir Precio_final

Fin
 ```



  ![Texto alternativo](images/24.png)

 3. El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

 ### Pseudocódigo:

 ```
 Inicio

// Declaración de variables
Entero Alumno
Entero Total

// Entrada de datos
Leer Alumno

// Condicionales anidados
Si Alumno >= 100 Entonces
    Total = Alumno * 65
SiNo
    Si Alumno >= 50 Entonces
        Total = Alumno * 70
    SiNo
        Si Alumno >= 30 Entonces
            Total = Alumno * 95
        SiNo
            Total = 4000

// Salida de resultados
Escribir Total

Fin
 ```

  ![Texto alternativo](images/25.png)

## Responder si los enunciados corresponden o no con las definiciones o conceptos aprendidos.

### Parte 1: Identificar Algoritmos

Responde si los siguientes enunciados representan un algoritmo. Justifica la respuesta:

1. Una página web. $-->$ **No, ya que no es una serie acciones dadas en orden, sino, que es una estructura para organizar texto.**

2. Una receta para hacer un pastel, donde se indican ingredientes y pasos a seguir. $-->$ **Si, ya que es una serie de pasos los cuales hay que seguir para hacer el pastel** 

3. "Piensa en un número y multiplícalo por otro". $-->$ **Si, ya que se le da la orden a algo/alguien de pensar en un número y multiplicarlo por otro, lo cual es una orden**

4. Un manual de instrucciones para armar un mueble, con pasos detallados y un orden claro. $-->$ **Si, ya que es una serie de instrucciones que hay que seguir para armar el  mueble, similar al pastel**

5. Una lista de compras organizada en orden alfabético $-->$ **Si, ya que se le da la orden de seguir una organización alfabética**

### Parte 2: Variables y Constantes

Indica si las siguientes afirmaciones describen una variable o una constante:

1. El valor de la gravedad en la Tierra, 9.8 m/s². $-->$ **Constante, la gravedad de la tierra no va a cambiar**

2. La edad de una persona calculada en base al año actual y su año de nacimiento. $-->$ **Variable, ya que la edad cambiara constantemente**

3. La cantidad de dinero en una cuenta bancaria. $-->$ **Variable, ya que la cantidad puede aumentar o disminuir**

4. La velocidad de la luz en el vacío, 299,792,458 m/s. $-->$ **Constante, ya que la velocidad de la luz no cambiará**

5. El radio de un círculo. $-->$ **Variable, ya que el radio puede cambiar dependiendo del diametro del mismo**

### Parte 3: Características de los Algoritmos

Responde si los siguientes enunciados cumplen con las características de un algoritmo. Justifica la respuesta:

1. Para elegir la ruta más corta entre varias ciudades, el algoritmo examina rutas candidatas, deteniéndose cuando los cambios en la distancia parecen lo suficientemente pequeños. $-->$ **No, ya que no cumple con la característica de ser finito**

2. Suma los números ingresados y muestra el resultado. $-->$ **Si, ya que suma los números ingresados por el usuario y muestra el resultado dando fin al proceso.**

3. Un conjunto de pasos para calcular el área de un rectángulo dado su base y altura. $-->$ **Si, ya que al redcibir los datos dados por el usuario calcula el área del rectangulo y entrega el resultado.**


4. El algoritmo cuenta el número de votos obtenidos por cada uno de los candidatos de una elección para presidente. Empieza solicitando el nombre del candidato y finaliza cuando se ingresa el valor -1. $-->$ **Si, ya que cuenta el número de votos, tiene un dato de entrada que es el nombre y tiene un fin cuando se ingresa el valor -1**

# Parte 4: Comprensión de Herramientas

Indica si las siguientes afirmaciones son ciertas o falsas respecto al pseudocódigo y diagramas de flujo:


1. El pseudocódigo utiliza símbolos estándar para representar las operaciones lógicas. $-->$ **No**

2. Los diagramas de flujo son una representación gráfica de un algoritmo $-->$ **Si**

3. El pseudocódigo debe estar escrito en un lenguaje de programación especifico $-->$ **No**

4. Un diagrama de flujo siempre debe tener un inicio y un final claramente definidos. $-->$ **Si**

# Parte 5: Estructuras de control

Describe para qué sirven las estructura de control. Redacta dos ejemplos, uno de tu vida diaria, es decir cuando tienes que tomar desiciones en tus actividades diarias y otro ejemplo en el que se tengan que utilizar cálculos matemáticos para tomar una u otra desición

Las estructuras de control son importantes para dirigir el flujo de ejecución de una acción

* En mi vida cotidiana un ejemplo estructura de control pueden ser los pasos o el flujo que tomo desde que me despierto hasta que llego a la universidad, doy clases, etc.

* Supongamos que estamos en un restaurante y tenemos una cantidad de dinero limite, analizamos los diferentes precios de las diferentes comidas y con base en nuestro presupuesto tomamos desiciones sobre que pedir, varias opciones como un plato caro pero sin bebida, o un plato barato con bebida, etc. En este problema analizariamos la diferencia de precios de los platos del restaurante con el presupuesto que tenemos.

