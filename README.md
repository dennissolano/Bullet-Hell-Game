# Bullet Hell Game

Bullet Hell es un género de videojuegos en los que el jugador controla un personaje u objeto, que dispara contra hordas de enemigos que van apareciendo en pantalla. Existen distintos subgéneros y se diferencian entre otros aspectos principalmente por la movilidad que tiene el protagonista, algunos ejemplos de estos son:

- *Fixed shooter*: el protagonista puede moverse a lo largo de un eje y los enemigos atacan desde una única dirección.
- *Multi-directional shooter*: el protagonista puede rotar y moverse en cualquier dirección.


### Características del juego

- El protagonista se encontrará en el centro del área de juego y podrá girar sobre su propio eje trescientos sesenta grados.

- El protagonista tendrá una barra de vida con un valor máximo de 100% y un valor mínimo de 0%.

- Los enemigos atacarán al protagonista desde cuatro direcciones posibles: arriba, abajo, izquierda y derecha.

- Existirán al menos tres tipos de enemigos.

 	- Los enemigos tendrán tres atributos que los diferencien, los principales serán: vida, daño de ataque y armadura.

- Existirán tres tipos de armas.

	- El daño que pueden infligir será lo que las diferencie.

 	- Dado que el el arma 1 es la que posee el menor daño esta tendrá la posibilidad de infligir daño crítico (de forma aleatoria ) por encima o debajo del daño del arma 2. Esto con el objetivo de que ambas armas sean utilizadas.

 	- En todo momento se tendrá a disposición el arma 1 y el arma 2; el arma 3 que es la más potente tendrá un tiempo de recarga para volver a ser utilizada.

- Estarán presentes los siguientes contadores:

 	- Contador de tiempo transcurrido.
 	- Contador de puntuación actual.
 	- Contador de puntuación más alta de la sesión de juego.

### Observaciones

- El juego correrá en la plataforma Android.

- Se busca que el jugador adquiera una capacidad de coordinación entre el disparar y la selección de armas.

### Interfaz Gráfica

**Pendiente dibujo preliminar**

- **Área de juego**

	Estará dividida en tres sectores:

	- Sector 1: Margen superior, contadores de tiempo, puntuación y puntuación más alta.

	- Sector 2: Centro, área de juego donde está el protagonista y los enemigos.

	- Sector 3: Margen inferior, botones de selección de arma.

- Por simplicidad se utilizarán figuras geométricas como cuadrados, rectángulos, círculos, triángulos entre otros y combinaciones de estos, para la representación del protagonista y los enemigos.

- Los disparos representados por círculos de distinto tamaño, este tamaño va a depender del daño que inflija el arma. La trayectoria que siga el proyectil va a ser rectilínea. Hay dos posibilidades de apreciar el disparo: movimiento del proyectil a través del espacio hasta impactar el enemigo o una línea continua que impacte el enemigo y desaparece.

