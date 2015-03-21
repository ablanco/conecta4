# Conecta 4

El famoso de juego de conecta 4 implementado en LISP, utilizando el conocido algoritmo de inteligencia artificial minimax.

- Consideremos un tablero con forma de retícula de 7 columnas con 6 celdas en cada una.
- Hay dos jugadores que juegan por turnos. Las piezas se colocan dejándolas caer desde lo alto de una columna que no está completa, y la pieza se coloca en la posición libre más baja de dicha columna.
- El juego acaba cuando algún jugador logra tener en el tablero 4 fichas adyacentes alineadas en horizontal, vertical o en diagonal, y ese jugador gana la partida. En caso de que el tablero se llene y ningún jugador haya logrado ganar, se acaba la partida con resultado de empate.
