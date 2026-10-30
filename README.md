# Juego 2 - Snake

## Descripción del repositorio

Este repositorio contiene el archivo `snake.py`, que corresponde al videojuego Snake desarrollado en Python, y el 
archivo `README.md`, donde se describen las modificaciones realizadas.

El juego consiste en controlar una serpiente mediante las flechas del teclado para alcanzar la comida y aumentar su tamaño, evitando 
chocar con los bordes de la ventana o con su propio cuerpo.

## Modificaciones realizadas

### 1. Movimiento aleatorio de la comida

Se agregó la funcionalidad para que la comida se mueva aleatoriamente por la pantalla, avanzando un paso en distintas 
direcciones. Además, se estableció una condición que evita que salga de los límites de la ventana, haciendo que el jugador tenga 
que seguirla para poder alcanzarla.

### 2. Colores aleatorios para la serpiente y la comida

Se modificó el juego para que, cada vez que se inicia una partida, la serpiente y la comida tengan colores diferentes 
seleccionados aleatoriamente entre cinco opciones: azul, verde, amarillo, morado y naranja.

Esto permite que cada partida tenga una combinación de colores distinta, evitando que la serpiente y la comida compartan el mismo color.
