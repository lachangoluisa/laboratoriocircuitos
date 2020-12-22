1.-OBJETIVOS

Explicar y demostrar experimentalemnte la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de corrientes.

2.-MARCO TÉORICO

Conceptos básicos

**Lazo**Definimos lazo como cualquier trayectoria cerrada alrededor de un circuito, se da comienzo en el terminal de cualquiera componente, puede ser cualquiera y se recorre los terminales de todos los demás componentes que estén en el camino hasta llegar hasta el punto inicial.

Un lazo no puede pasar más de una vez por el mismo componente.

**Malla**Una malla es un lazo que no contiene otros lazos en su interior, es decir que comienza en el terminal de un componente cualquiera y el final del recorrido es el terminal del mismo componente, pero sin lugar a que exista otra malla en su interior.

**Nodos**Punto en el que se conectan dos o más elementos de un circuito. Lazos: Camino que da la corriente.

**Ramas**La unión de 2 nodos.

Leyes de Kirchhoff

las reglas de Kirchhoff, establecidas por G. R. Kirchhoff (1824-1887) a mediados del siglo XIX. Son aplicaciones convenientes de las leyes de conservación de la carga y la energía.

La primera regla de Kirchhoff, o regla de los nodos

**"La corriente entrante a un nodo es igual a la suma de las corrientes salientes"**

Se basa en la conservación de la carga eléctrica que ya se usó al deducir la regla para resistores en paralelo. Esa regla afirma que, en cualquier punto de unión, la suma de todas las corrientes que entran al nodo debe ser igual a la suma de todas las corrientes que salen del nodo.

∑Iadentro=∑Iafuera

La segunda regla de Kirchhoff o Ley de voltaje de Kirchhoff 

**"La suma de los voltajes alrededor de una trayectoria o circuito cerrado debe ser cero"**

nos dice que la suma de los voltajes alrededor de una malla es igual a cero.

∑Vsubida=∑Vbajada

Propiedades de la ley de voltaje de Kirchhoff:

   • Puedes trazar una malla que comience en cualquier nodo. Si caminas alrededor de la      malla y terminas en el nodo inicial, la suma de los voltajes de la malla es igual a      cero.

  •	Si un circuito tiene múltiples mallas, la ley de voltaje de Kirchhoff es válida para     cada una.

Pasos para resolver un circuito

•	Identificar cuáles son las mallas.

•	Asignarle una corriente a cada malla.

•	Escribir el sistema de ecuaciones basado en la segunda ley de Kirchhoff.

•	Resolver el sistema de ecuaciones.

•	Encontrar el valor de las corrientes de cada voltaje aplicando la Ley de Ohm.
![WhatsApp Image 2020-12-22 at 12 04 03 PM](https://user-images.githubusercontent.com/76057459/102918250-9274c580-4454-11eb-908c-4d063822225d.jpeg)

3.-DIAGRAMAS

![diagrama](https://user-images.githubusercontent.com/76057459/102248205-ed477380-3ece-11eb-9a08-bca356ad8b4e.PNG)

Diagrama 3.1: Circuito Resistivo mixto

4.-LISTA DE COMPONENTES
|cantidad|Material o equipo|
|---|---|
|1|Fuente de voltaje C.D.|
|2|Multímetros digitales|
|1|Resistor de 1k Ohm|
|2|Resistores de 2.2k Ohm|
|1|Resistor de 1.8k Ohm|
|1|Resistor de 3.9k Ohm|
|1|Protoboard|

5.-EXPLICACIÓN

5.1 Arme el circuito que se muestra en el Diagrama 3.1.

5.2 Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 5.1.

Tabla 5.1: Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

|VARIABLE|VALOR CALCULADO| VALOR MEDIDO|
|---|---|---|
|VR1(V)| 2.05|2.46|
|IR1(mA)| 2.05|2.05|
|VR2(V)|4.22|4.25|
|IR2(mA)|1.08|1.08|
|VR3(V)|2.09|2.12|
|IR3(mA)|0.95|0.965|
|VR4(V)|2.09|2.12|
|IR4(mA)|0.95|0.965|
|VR5(V)|3.69|3,70|
|IR5(mA)|2.05|2.054|

5.3 Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada, considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con signo negativo. Anote los resultados en la tabla 5.2.

Tabla 5.2: Verificación de la LVK.
                           
![2](https://user-images.githubusercontent.com/76057459/102257394-aeb7b600-3eda-11eb-8678-af68068f7dd9.png)

5.4 Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando con signo positivo las corrientes que entran al nodo y con signo negativo las que salen del nodo. Anote los resultados en la tabla 5.3.

Tabla 5.3: Verificación de la LCK.

![1](https://user-images.githubusercontent.com/76057459/102257412-b4150080-3eda-11eb-895c-c001426483ff.png)

5.5 Compare los resultados medidos con los valores obtenidos al analizar el circuito analíticamente y concluya al respecto.

PROCEDIMIENTO

Malla 1

10+1KI_1-3.9K(I_1-I_2)-1.8KI_2=0

10-6.7KI_1+3.9KI_2=0

6.7I_1-3.9I_2=10 (1)

Malla 2

-2.2KI_2-2.2KI_2-3.9K(I_2-I_1)=0

-8.3KI_2+3.9KI_2=0 (2)

Sistema de Ecuaciones con (1) y (2)

{6.7I_1-3.9I_2=10

{3.9I_1-8.3I_2=0

Resolviendo :

I_1=2.053 mA Esta es la corriente que circula en la primera maya

I_2=0.965 mA Esta es la corriente que circula en la segunda maya

Para encontrar los voltajes ocupamos la ley de Ohm

V=I*R

VR_1=2.053mA*1K

VR_1=2.053 V

Para encontrar el voltaje en la resistencia 2 debemos hacer una diferencia entre la corriente 1 y la corriente 2

IR_2=I_1-I_2

IR_2=2.053 mA-0.965 mA

IR_2=1.088 mA

VR_2=1.088 mA*3.9K

VR_2=4.24V

VR_3=0.965 mA*2.2K

VR_3=2.12V

VR_4=0.965 mA*2.2K

VR_4=2.12V

VR_5=2.053mA*1.8K

VR_5=3.69 V

Para poder calcular el error debemos aplicar la siguiente formula

error%=((Valor teórico-Valor medido)/(Valor teórico))*100%
porcentaje de error

![WhatsApp Image 2020-12-22 at 1 47 43 PM](https://user-images.githubusercontent.com/76057459/102922676-69583300-445c-11eb-983d-bcd986a39351.jpeg)
6.-DESCRIPCION DE PREREQUISITOS Y CONFIGURACIÓN

•	Tinkercat: Es una herramienta online de Autodesk, que permite la simulación de circuitos, al igual que permite dibujar esquemas circuitales de forma sencilla.

8.-CONCLUCIONES
se concluye que si una corriente  se divide  en  en dos o mas corrientes ,esta corriente sera igual a la inicial

La clave esta en interpretar correctamente el circuito para extrapolarlo en un sistema de ecuaciones equivalente, que represente la realidad física del comportamiento del mismo.

El voltaje en dos ramas en paralelo siempre es el mismo, con lo cual podemos decir que el voltaje en R1 sera igual al voltaje en R2 que a su vez sera igual al voltaje de la fuente
RECOMENDACIONES
Para la practica de tinkercad se debe tener en cuenta que la corriente en el multimetro se mide en serie  respecto al elemento
para medir voltaje en el multimetro se debe realizar en paralelo respecto al elemento a medir
Colocar bien los signos al recorrer una malla del circuito, una de las reglas mnemotecnias que a mi me da buen resultado es la siguiente.

9.-BIBLIOGRAFIA

Douglas C. Giancoli. Física para ciencias e ingenierıa. Pearson, 2008.
Kerchner, R. M., Corcoran, G.F. (1975): Circuitos de corriente alterna. La Habana: Pueblo y Educación.
Ayllón Fandiño, E. (1987): Fundamentos de la teoría de los circuitos eléctricos II. La Habana: Pueblo y Educación.

10.-ANEXOS

![circuito](https://user-images.githubusercontent.com/76057459/102247810-701bfe80-3ece-11eb-80a9-50a662b43d18.jpg)
Imagen 1:Circuito elaborado en tinkercat
![WhatsApp Image 2020-12-22 at 12 32 16 PM](https://user-images.githubusercontent.com/76057459/102918170-72450680-4454-11eb-8cc1-d1c79ea46138.jpeg)
![WhatsApp Image 2020-12-22 at 12 28 11 PM](https://user-images.githubusercontent.com/76057459/102918190-7a9d4180-4454-11eb-982e-fdf07dc9c1b6.jpeg)
![WhatsApp Image 2020-12-22 at 12 27 00 PM](https://user-images.githubusercontent.com/76057459/102918218-82f57c80-4454-11eb-8b81-b2c7cd3fb2ff.jpeg)
![WhatsApp Image 2020-12-22 at 12 26 05 PM](https://user-images.githubusercontent.com/76057459/102918231-8852c700-4454-11eb-8d2d-f43e1f64640e.jpeg)
![WhatsApp Image 2020-12-22 at 12 23 19 PM](https://user-images.githubusercontent.com/76057459/102918242-8e48a800-4454-11eb-97a3-89b5f076b744.jpeg)
