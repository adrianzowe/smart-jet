# SMARTJET

>Adrián García Padilla

>Francisco Quesada Muñoz
>Antony Franco Rivero Meza
>David Robles del Viso


## 1. Introducción  

El presente documento corresponde a la memoria del trabajo de la asignatura Sistemas Inteligentes el cual detalla el estudio y desarrollo de un controlador difuso, en Unity 3D, para el control automático de vuelo de un avión.

Para la realización de este trabajo se ha dividido el desarrollo en dos fases. 
La primera se centra en estudiar los principios básicos de vuelo, identificando las partes o módulos de una aeronave que se deberá manejar para lograr el objetivo.

En la segunda fase se desarrolla el código en C#....


## 2. Objetivos

El objetivo 

Como objetivo nos proponemos desarrollar un controlador difuso que sea capaz de controlar los parámetros del avión para así poder estabilizarse cada vez que cambie de dirección o choque contra algún obstáculo.

## 3. Funcionamiento de la práctica
Para comprobar el correcto funcionamiento de la práctica y que el avión es capaz de corregir cualquier maniobra y de autoestabilizarse en los siguientes casos:

+  **Caída libre:** al comenzar el avión caerá desde una distancia definida, con velocidad igual a cero y con distintas posiciones que se obtendrán aleatoriamente mediante una función que calcule el ángulo con el que comenzará.

+ **Control manual:** mediante el teclado se podrá controlar el avión para poder desestabilizarle cambiando tanto el cabeceo como el aleteo. Los controles del avión serán:
    + *Cabeceo:* teclas arriba y abajo.
    + *Alabeo:* teclas derecha e izquierda.

+ **Obstáculos:** se ha creado un mapa con diferentes obstáculos, como una montaña y un terreno irregular para poder comprobar cómo es capaz de volver a estabilizarse tras chocar contra algún objeto.

## 4. Lógica y código del controlador
