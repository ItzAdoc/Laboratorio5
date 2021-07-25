# Laboratorio 5

__1. Objetivos__

*Objetivo General*
* 

*Objetivos Específicos*


__2. Marco Teórico__ 


__3. Explicación del Procedimiento__

_*CIRCUITO PRINCIPAL*_

1. Se hace 0 a la fuente de 2V.
2. Se calcula la resistencia total y con ella corriente total.
3. Se calcula la corriente en R5.
4. Se calcula el voltaje de R5 con leyes de Kirchhoff. 
5. Se hace 0 la fuente de 2V.
6. Se calcula la resistencia total y con ella corriente total.
7. Se calcula la corriente en R5.
8. Se calcula el voltaje de R5 con leyes de Kirchhoff. 
9. Se suma o resta los valores obtenidos tanto para corriente como para voltaje, en este caso se suman porque tienen el mismo sentido.


_*CIRUCITO DE THÉVENIN*_

1.	Se elige que parte del circuito se reemplazara por el de Thévenin, en este caso es todo menos R5. 

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C1.png)

2.	Se reemplaza todas las fuentes de voltaje por un corto y se elimina R5.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C2.PNG)

3.	Se calcula la resistencia total del circuito que nos queda, esta resistencia será la equivalente a la resistencia de Thévenin. 

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C3.PNG)

4.	Se vuelve a ubicar las fuentes de alimentación y se calcula el voltaje de ab.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C4.PNG)

5.	Como por R4 no circula ningún voltaje o corriente se la puede eliminar y se calcula el voltaje de R3 que es mismo que el voltaje de ab.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C5.png)

6.	Se procede a calcular con el método más conveniente, en este caso será por de método de superposición 

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C6.PNG)

7.	Se hace cero a la fuente de 2V.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C7.PNG)

8.	Se calcula el voltaje de R3, para ello se necesita la resistencia total del circuito.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C8.PNG)

9.	Con esta RT se saca la IT.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/C9.PNG)

10.	Se saca el voltaje que circula por R3 aplicando leyes de Kirchhoff.

11.	Ahora se hace 0 a la fuente de 12V.

12.	Se saca el voltaje de R3 con divisor de voltaje, para ello necesitamos RT. 

13.	Se suma o resta los voltajes obtenidos cuando cada una de las fuentes fue 0. En este caso se suma puesto que tiene el mismo sentido y con esto se obtiene el voltaje de R3 que es voltaje de ab.

14.	Con los valores obtenidos de resistencia y voltaje se crea el circuito de Thévenin.

15.	Se añade al circuito de Thévenin R5.

16.	Se calcula RT. Y con RT se saca la corriente total que es la misma para todo el circuito y el voltaje de R5.

Por último se anotá los valores obtenidos en las tablas.

Tabla 5.1. Valores del Circuito Equivalente de Thévenin

Tabla 5.2. Comprobación del Teorema de Thévenin.


__4. Respuesta a Interrogantes y Calculo de Error__

4.1. Arme el circuito que se muestra en la figura 5.1.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.1.png)

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.1a.png)

4.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.1

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.2.png)

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.2a.png)

4.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.3.png)

4.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.4.png)

4.5. Implemente el circuito equivalente de Thévenin agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.5.png)

![](https://github.com/ItzAdoc/ImagenesLab5/blob/main/4.5a.png)
Calculo de Error

+ Error en los valores equivalentes de Thévenin

+ Error en el circuito original

+ Error en el Circuito Equivalente De Thévenin
