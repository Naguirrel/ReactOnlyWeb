# Snake – Arcade Edition

## Descripción General

Snake Arcade Edition es una implementación del clásico juego de Snake desarrollada con React (vía CDN) y Babel, sin ninguna herramienta de build. Todo el código reside en un único archivo `index.html` que puede abrirse directamente en el navegador.

El juego consiste en controlar una serpiente que se mueve por un tablero de 20x20 celdas. El objetivo es comer la mayor cantidad de comida posible para crecer y acumular puntos, sin chocar contra las paredes ni contra el propio cuerpo.

La aplicación está estructurada en los siguientes componentes React:

- App: contenedor principal, gestiona el estado global del juego.
- Board: renderiza el tablero de juego.
- Snake: representa visualmente la serpiente celda por celda.
- Food: muestra la comida en el tablero.
- Score: muestra el puntaje actual.
- Level: muestra el nivel actual, el cual incrementa cada 3 puntos.

A medida que el jugador acumula puntos, la velocidad de la serpiente aumenta y el nivel sube, incrementando la dificultad de forma progresiva.

---

## Instrucciones de Juego

### Requisitos

Se requiere únicamente un navegador moderno (Chrome, Firefox, Edge o Safari). No es necesaria ninguna instalación ni servidor.

### Inicio

1. Abrir el archivo `index.html` en el navegador.
2. En la pantalla de inicio, presionar el botón Iniciar o la tecla Enter.

### Controles

| Tecla | Acción |
|---|---|
| Flecha arriba | Mover hacia arriba |
| Flecha abajo | Mover hacia abajo |
| Flecha izquierda | Mover hacia la izquierda |
| Flecha derecha | Mover hacia la derecha |
| Enter | Iniciar o reiniciar el juego |

### Reglas

- La serpiente se desplaza de forma continua en la dirección indicada.
- Al consumir la comida, la serpiente crece y se suma un punto al puntaje.
- Cada 3 puntos, el nivel aumenta y la serpiente se mueve con mayor velocidad.
- El juego finaliza si la serpiente choca contra una pared o contra su propio cuerpo.
- Al terminar la partida, es posible reiniciar desde la pantalla de Game Over mediante el botón Reiniciar o la tecla Enter.
