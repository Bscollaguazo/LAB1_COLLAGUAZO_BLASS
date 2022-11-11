# LAB1_COLLAGUAZO_BLASS

Laboratorio 1 de fundamentos de circuitos (herramientas ,seguridad y càlculos de circuitos)

1. OBJETIVOS
2. 1.1 Objetivos Generales.

-Conocer las herramientas con las cuales vamos a realizar la practica.

-Conocer los diferentes circuitos

-Aprender leyes y teorias para analizar circuitos

-Lograr que el estudiante arme un circuito en un simulador virtual

1.1.2 Objetivos Especificos

-Conocer detalladamente el uso del multimetro sus diferetes funciones para medir el voltaje, la intensidad etc de un circuito electrico, ademas de eso el uso del soldador (cautin) , el uso del protoboad, el funcionamiento de las resitencias, el uso del estaño, y las demas herramientas.

-Conocer que tenemos 3 circuitos basicos como son el circuitos en serie, eeparalelo y mixto.

-Aprender sobre la ley de kircchoff, la ley de ohm ya que son leyes que nos permiten realizar calculos en los diferentes circuitos electricos.

-Saber conectar un circuito en protoboad, usando resistensias, fuentes de alimentasion y conectandolo de la manera que el docente nos indique, si es un circuito serie, paralelo o mixto.

2. MARCO TEÓRICO

2.1.1 MUltimetro.-Es un instrumento portatil que se usa para medir magnitudes electricas como corrientes y potencias, se puede medir corriente continua o alterna los multimetros o tambien conocidos como tester en la actualidad son digitales, esta compuesto por su pantalla, una perrilla y sus dos cables positivo y tierra.

2.1.2 SOLDADOR.- Es un instrumento el cual consta de 3 partes un cable de conección a 110 v, una parte fija de madera o plastico y su punta de metal, su punta se calentara a una temperatura capaz de derretir el estaño. esto nos sirve para hacer sueldas de componentes electronicos, ademas de placas en baquelitas.

2.1.3 PROTOBOAD.- Es una especie de tablero con orificios, en la cual se pueden insertar componentes electrónicos y cables para armar circuitos. Como su nombre lo indica, esta tableta sirve para experimentar con circuitos electrónicos, con lo que se asegura el buen funcionamiento del mismo.

2.1.4 RESISTENCIA.- La resistencia electrica de un objeto es una oposion al paso de la corriente electrica.

2.1.5 CIRCUITO EN SERIE.- Este es un circuito que su caracteristica principal es que sus bornes o resistencias van una tras de la otra en este circuito la tension varia.

2.1.6 CIRCUITO PARALELO.- Este es un circuito el cual sus resistencias estan conectadas de forma que todos sus terminales coinciden entre sí en este circuito no varia la tensión.

2.1.7 CIRCUITO MIXTO.- Este circuito es un circuito que se compone de un circuito en serie con un circuito en paralelo.

2.1.8 LEY DE KIRCCHOFF.-Las leyes de Kirchhoff son dos igualdades que se basan en la conservación de la energía y la carga en los circuitos eléctricos. En estas leyes vamos a ver lo que es un NODO y lo que es una MALLA, el Nodo  es un punto donde dos o más elementos o ramas de un circuito cerrado tienen una conexión común. la Malla es un lazo cerrado o un circuito cerrado de toda la conexión.

2.1.9 LEY DE OHM.-La ley de Ohm se usa para determinar la relación entre tensión, corriente y resistencia en un circuito eléctricO, aqui tenemos una formula de la cual despejamos los demas componentes, la formula es V= I.R (Voltaje= Intensidad . Resistencia)

3. EXPLICACIÓN DEL PROCEDIMIENTO

Circuito Resistivo Mixto (TINKERCAD)

![](https://github.com/Bscollaguazo/LAB1_COLLAGUAZO_BLASS/blob/main/circuito.png)

Diagrama Esquematico

![](https://github.com/Bscollaguazo/LAB1_COLLAGUAZO_BLASS/blob/main/diagrama.png)

Se procede a ultilizar el simulador tinkercad para realizar mediciones de voltaje e intensidad de corriente en el circuito electrico mixto 

Medicion de voltaje:

![](https://github.com/Bscollaguazo/LAB1_COLLAGUAZO_BLASS/blob/main/medicionv.png)

Medicion de intensidad de corriente:

![](https://github.com/Bscollaguazo/LAB1_COLLAGUAZO_BLASS/blob/main/medicioni%20(2).png)

Se procede a realizar el calculo analiticamente

Para resolver este circuito mixto se procede a utlizar los conceptos de resistencias en serie y paralelo para asi poder encontrar los respectivos voltajes e intensidad  de corriente en las diferentes resistencias.

![](https://github.com/Bscollaguazo/LAB1_COLLAGUAZO_BLASS/blob/main/calculoanalitico.jpg)

Resolucion de circuito mixto:

Se observa que la resistencia 3 y 4 estan en serie por lo que sumamos las 2 resistencias:

R_s=2.2kΩ+2.2kΩ=4.4kΩ

El resultado de esta resistencia queda en paralelo con la resistencia 2 :

R_p=(3.9kΩ)(4.4kΩ)/3.9kΩ+4.4kΩ

R_p=17.16kΩ/8.3kΩ

R_p=2.07kΩ

Con esto todas las resistencias quedan en serie por lo que se sumas y nos da una resistencia equivalente:

R_e=1kΩ+2.7kΩ+1.8kΩ

Para finalizar con la resistencia equivalente y usando la formula de Ohm obtenemos los valores de voltaje e intensidad de corriente de las diferentes resistencias 

![](https://github.com/Bscollaguazo/LAB1_COLLAGUAZO_BLASS/blob/main/tabla01.jpg)


