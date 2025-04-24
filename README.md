# Pac-Man en Ensamblador MARIE

Este proyecto implementa una versión simplificada del clásico juego Pac-Man, desarrollada completamente en lenguaje ensamblador para la arquitectura MARIE (Machine Architecture that is Really Intuitive and Easy).

## Características

- Movimiento automático de Pac-Man y los fantasmas (Blinky, Pinky, Inky y Clyde).
- Detección de colisiones con paredes, bolitas, esteroides y fantasmas.
- Sistema de puntuación y contador de vidas.
- Respawn de Pac-Man o fantasmas tras colisiones.
- Renderizado de personajes y escenarios en una matriz de display de memoria.

## Tecnologías

- Lenguaje: Ensamblador MARIE
- Simulador: MARIE Simulator (disponible en marie.js.org o como aplicación de escritorio)

## Estructura del Código

- `main.mas`: Código principal del juego.
- Subrutinas para:
  - Movimiento y pintura de Pac-Man y fantasmas.
  - Verificación de colisiones.
  - Cálculo de dirección en pantalla (`Y * 16 + X + offset`).
  - Multiplicación por sumas sucesivas.

## Requisitos

- Simulador de MARIE instalado.
- Conocimiento básico del conjunto de instrucciones MARIE.

## Autores

Este proyecto fue desarrollado como trabajo final para el curso de Organización de Computadores.
