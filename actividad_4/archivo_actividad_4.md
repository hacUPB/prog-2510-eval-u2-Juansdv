
# Retos en Python

1. Se requiere obtener la distancia entre dos puntos en el plano cartesiano, tal y como se muestra en la figura 1. Realice un diagrama de flujo y pseudocódigo que representen el algoritmo para obtener la distancia entre esos puntos.

### Codigo:

```
import math

X1 = float(input("Digita la coordenada para X1\n"))
X2 = float(input("Digita la coordenada para X2\n"))

Y1 = float(input("Digita la coordenada para Y1\n"))
Y2 = float(input("Digita la coordenada para Y2\n"))

print("La distancia entre los dos puntos en el plano es: \n ",math.sqrt((X2-X1)**2 + (Y2-Y1)**2))

```

 
 2. Una modista, para realizar sus prendas de vestir, encarga las telas al extranjero. Para cada pedido, tiene que proporcionar las medidas de la tela en pulgadas, pero ella generalmente las tiene en metros. Realice un algoritmo para ayudar a resolver el problema, determinando cuántas pulgadas debe pedir con base en los metros que requiere. Represéntelo mediante un diagrama de flujo y pseudocódigo (1 pulgada = 0.0254 m).

 ### Codigo:

```
tela = float(input("¿Cuantos metros de tela desea comprar?\n"))

print("Debe comprar", tela/0.0254 ,"pulgadas de tela")
```

3. Se requiere determinar la hipotenusa de un triángulo rectángulo. ¿Cómo sería el diagrama de flujo y el pseudocódigo que representen el algoritmo para obtenerla? Recuerde que por Pitágoras se tiene que: C^2 = A^2 + B^2.

### Codigo:

```

import math

cat_a = float(input("Digite el valor del primer cateto \n"))
cat_b = float(input("Digite el valor del segundo cateto \n"))

print(math.sqrt((cat_a)**2 + (cat_b)**2 ))

```


4. Se requiere determinar la edad actual de una persona basándose en su fecha de nacimiento. Además, es necesario establecer si la persona ya ha cumplido años en el año en curso, si aún no lo ha hecho, o si hoy es su cumpleaños, para celebrarlo. La fecha de nacimiento y la fecha actual estarán representadas mediante tres variables: día, mes y año.

### Codigo:

```

import datetime

fecha_actual = datetime.date.today()

dia_nacimiento = int(input("Digita el dia de tu cumpleaños \n"))
mes_nacimiento = int(input("Digita el mes de tu cumpleaños \n"))
año_nacimiento = int(input("Digita el año de tu cumpleaños \n"))

edad = int(fecha_actual.year - año_nacimiento )

if fecha_actual.month < mes_nacimiento or fecha_actual.month == mes_nacimiento and fecha_actual.day < dia_nacimiento:
    edad = edad - 1
else:
    edad

if fecha_actual.day == dia_nacimiento and mes_nacimiento == fecha_actual.month:
    print("Feliz Cumpleaños")

else:
    print("ienes",edad,"años")

```


5. Realice un algoritmo que permita determinar el sueldo semanal de un trabajador con base en las horas trabajadas y el pago por hora, considerando que a partir de la hora número 41 y hasta la 45, cada hora se le paga el doble, de la hora 46 a la 50, el triple, y que trabajar más de 50 horas no está permitido. Represente el algoritmo mediante pseudocódigo.

### Codigo:

```

horas_trabajadas = float(input("Ingrese las horas trabajadas: \n"))
pago_hora = float(input("Ingrese el pago por hora: \n"))

if horas_trabajadas > 50:
    print("No se permite trabajar más de 50 horas.")
else:
    if horas_trabajadas <= 40:
        sueldo_semanal = horas_trabajadas * pago_hora
    else:
        horas_normales = 40
        if horas_trabajadas <= 45:
            horas_dobles = horas_trabajadas - 40
            sueldo_semanal = (horas_normales * pago_hora) + (horas_dobles * pago_hora * 2)
        else:
            horas_dobles = 5
            horas_triples = horas_trabajadas - 45
            sueldo_semanal = (horas_normales * pago_hora) + (horas_dobles * pago_hora * 2) + (horas_triples * pago_hora * 3)
    
    print("Su sueldo semanal es:", sueldo_semanal)

```





