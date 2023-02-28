# INFORME-PROYECTO-TERCER-PARCIAL

INTEGRANTES:

* Aguirre Johan 
* Calahorrano Sarahi 
* Lara Melany


*1. OBEJTIVOS*

  *Objetivo General:*
  * Realizar un circuito aplicativo, mediante el uso de componentes electrónicos como es el sensor de temperatura LM35 y el amplificador operacional LM358, para ver el
  funcionamiento de los mismos cuando se los implementa en un circuito común. 

  *Objetivos Específicos:*
  
  - Verificar el datasheet de los dos componentes nuevos 

- Observar el comportamiento del sensor de temperatura LM35 

- Observar el comportamiento del amplificador operacional LM358 

*2. MARCO TEÓRICO*

![image](https://user-images.githubusercontent.com/105020538/221754705-ec8b2b8a-6524-4fea-9170-52fce6e80943.png)

![image](https://user-images.githubusercontent.com/105020538/221754743-50bfc417-54e4-4290-bdd6-060814647fb9.png)

![image](https://user-images.githubusercontent.com/105020538/221754790-98f12142-6199-4321-824d-58db4413b670.png)

*3.	EXPLICACIÓN DEL PROCEDIMIENTO*

*MATERIALES*

![image](https://user-images.githubusercontent.com/105020538/221754357-67cf2a5f-cbe0-46d6-9d3f-d74eae5ca79f.png)

*PROCEDIMIENTO*

* Colocaremos el sensor de temperatura LM35 tomando en cuenta el datasheet de conexiones respectivas. 

* Como se necesita amplificar la señal que proporciona la salida de este sensor más una condición, conectaremos un amplificador operacional LM358, solo ocuparemos uno de los dos que lo forman. 

* En el pin 3 del LM358 ingresara la señal del sensor de temperatura LM3 

* En el pin 2 conectaremos el potenciómetro de 10kΩ, colocándole como un divisor de voltaje entre positivo y negativo 

* Como la salida del LM358 me permite tener tanto una señal negativa como positiva, conectaremos dos diodos led en ambas polaridades 

* Procedemos a conectar una fuente de 6v, ya que ambos componentes funcionan en estos voltajes

*DIAGRAMA ESQUEMATICO*

![Imagen de WhatsApp 2023-02-28 a las 10 55 32](https://user-images.githubusercontent.com/105056762/221911483-44a8f4ff-d3c0-42d9-bfbc-89abf3e28204.jpg)

*CIRCUITO FISICO*

![image](https://user-images.githubusercontent.com/105020538/221755316-1bef7b9e-59c9-4c11-94c1-7fa305550afe.png)

*4. ANALIZAR CADA ELEMENTO DEL CIRCUITO*

*Sensor de temperatura LM 35* 

El LM35 funciona básicamente como un sensor de temperatura el cuál por cada grado centígrado enviará 10 mv a su salida, lo ocupamos en este circuito para ser comparado con otro voltaje previamente establecido con el potenciometro de 10k. 

*Amplificador operacional LM 358* 

El LM358 específicamente en este circuito actúa como un commparador de voltaje que produce una señal alta o baja en función de si la señal en la entrada no inversora es mayor o menos que la señal en la entrada inversora. 
 
*Potenciómetro 10 kΩ*

Este elemento nos sirve para preestablecer un valor de voltaje para ser comparado con el sensor de temperatura, lo podemos regular a la temperatura que queramos mediante la lógica 10mv=1 grado centígrado.  

*Diodos LED* 

Los diodos funcionan como luces piloto en nuestro circuito, usaremos dos, uno para ver si la temperatura ingresada al LM35 es menor al voltaje del potenciómetro y así mismo otro que se encenderá cuando el voltaje generado por el LM35 sea mayor, lo cual indica que nuestro sensor de temperatura posee un valor mayor. 

*Resistencias de 470* 

Las resistencias nos sirven para reducir la cantidad de corriente que entra a los diodos led para protegerlos y evitar que se quemen, esto prolongará su vida útil. 

*5. VIDEO*

https://youtu.be/IMWU9rcGOlE

*6. CONCLUSIONES* 

- Los sensores de temperatura son componentes eléctricos y electrónicos que, en calidad de sensores, permiten medir la temperatura mediante una señal eléctrica determinada. Dicha señal puede enviarse directamente o 
mediante el cambio de la resistencia. También se denominan sensores de calor o termosensores. 

- El amplificador de alta ganancia directamente acoplado, que en general se alimenta con fuentes positivas y negativas, lo cual permite que tenga excursiones 
tanto por arriba como por debajo de tierra 

*7. BIBLIOGRAFÍA*

- HetPro. (2018). Amplificadores. Recuperado de: https://hetpro-store.com/TUTORIALES/amplificador-operacional/  

- Sensors. (2021). El sensor de temperatura. Recuperado de: https://www.rechner-sensors.com/es/documentacion/knowledge/el-sensor-de-temperatura#:~:text=Los%20sensores%20de%20temperatura%20son,sensores%20de%20calor%20o%20termosensores.  

- Sensoricx. (2020). Circuito con amplificador. Recuperado de: https://sensoricx.com/circuitos-para-armar/modulo-sensor-de-temperatura-2/#:~:text=Con%20este%20circuito%2C%20podemos%20medir,los%20mismos%20entre%20otros%20procesos.
