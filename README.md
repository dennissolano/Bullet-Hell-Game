# Bullet Hell Game

Bullet Hell es un shooter en primera persona, es decir, es un videojuego de un género específico en el cual el jugador controla un personaje u objeto. El objetivo de Bullet Hell se basa disparar contra hordas de enemigos que aparecen continuamente en la pantalla desde diferentes ángulos. Existen distintos subgéneros para este tipo de juegos y se diferencian, entre otros aspectos, principalmente por la movilidad que tiene el protagonista, algunos ejemplos de estos son:

- *Fixed shooter*: el protagonista puede moverse a lo largo de un eje y los enemigos atacan desde una única dirección.
- *Multi-directional shooter*: el protagonista puede rotar y moverse en cualquier dirección.


### Características del juego

- El protagonista se encontrará en el centro del área de juego y podrá girar sobre su propio eje trescientos sesenta grados.

- El protagonista tendrá una barra de vida con un valor máximo de 100% y un valor mínimo de 0%.

- Los enemigos atacarán al protagonista desde cuatro direcciones posibles: arriba, abajo, izquierda y derecha.

- Existirán al menos tres tipos de enemigos.

 	- Los enemigos tendrán tres atributos que los diferencien, los principales serán: vida, daño de ataque y armadura.

- Existirán tres tipos de armas.

	- El daño que pueden infligir y las municiones será lo que las diferencie.

 	   - Dado que el el arma 1 es la que posee el menor daño esta tendrá la posibilidad de infligir daño crítico (de forma aleatoria ) por encima o debajo del daño del arma 2. Esto con el objetivo de que ambas armas sean utilizadas. Además el arma 1 contará con municiones infinitas.

 		- La segunda arma infligirá un poco más de daño que el arma 1 bajo circunstancias normales (es decir, que el arma 1 no acerte un golpe crítico). Pero al hacer más daño, esta contará con una cantidad limitada de balas.

 		- En todo momento se tendrá a disposición el arma 1 y el arma 2; el arma 3 que es la más potente tendrá un tiempo de recarga para volver a ser utilizada y contará con menos municiones que el arma 2.

- Estarán presentes los siguientes contadores:

 	- Contador de tiempo transcurrido.
 	- Contador de puntuación actual.
 	- Contador de puntuación más alta de la sesión de juego.

- Beneficios para el jugador:

    - Para mejorar la experiencia se dará al jugador posibilidad de curarse y conseguir mas municiones durante la partida asesinando objetivos.

    	- Se dará un 1% de probabilidades de que uno de los enemigos que está emergiendo sea un objetivo especial, lucirá exactamente como los demás pero si este es asesinado, otorga 10% de curación al jugador.
    	- Existe un 2% de probabilidades de que alguno de los enemigos emergentes otorgue municiones para el arma de nivel 2.
    	- Finalmente, existe un 0.5% de que uno enemigo emergente otorgue 1 munición para el arma de nivel 3.

### Observaciones

- El juego correrá en la plataforma Android.

- Se busca que el jugador adquiera una capacidad de coordinación entre el disparar y la selección de armas.

- ¿Cómo irán apareciendo los enemigos?

	- Básicamente es dependiente del tiempo. Entre más tiempo haya transcurrido aumentará la cantidad de enemigos que aparezcan y la variedad de estos. Para el segundo entregable se utilizará la función identidad y conforme se vaya avanzando se modificará la función.

### Interfaz Gráfica

**Pendiente dibujo preliminar**

- **Área de juego**

	Estará dividida en tres sectores:

	- Sector 1: Margen superior, contadores de tiempo, puntuación y puntuación más alta.

	- Sector 2: Centro, área de juego donde está el protagonista y los enemigos.

	- Sector 3: Margen inferior, botones de selección de arma.

- Por simplicidad se utilizarán figuras geométricas como cuadrados, rectángulos, círculos, triángulos entre otros y combinaciones de estos, para la representación del protagonista y los enemigos.

- Los disparos representados por círculos de distinto tamaño, su circunferencia va a depender del daño que inflija el arma. La trayectoria que siga el proyectil va a ser rectilínea. Hay dos posibilidades de apreciar el disparo: movimiento del proyectil a través del espacio hasta impactar el enemigo o una línea continua que impacte el enemigo y desaparece.

- Para crear el efecto del tiempo de recarga se aplicará al botón del arma 3 un control de opacidad. Cuando el arma sea utilizada la opacidad del botón se establece al 100%, conforme pase el tiempo de recarga va disminuyendo progresivamente la opacidad hasta 0% lo que indica que el arma puede ser utilizada nuevamente.