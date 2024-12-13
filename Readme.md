# Juego de las damas
## Funcionamiento
El juego consta de un **tablero de 8 x 8**. 
Las fichas blancas son un círculo (`'O'`) y las negras
se representan con una cruz (`'X'`). __Va ganando el juegador 
que más fichas tenga en el tablero__.
## Ordinograma
![Ordinograma de funcionamiento del programa](img/ordinograma.png)
## Tablero
El tablero del juego de damas es de __8 X 8__. Es un array tipo __char__ 
para almacenar las X y O, y las casillas vacías se representan con espacios (`' '`).

El código que lo almacena sería algo así:

```java
char[][] tablero = {
        {'X', ' ', 'X', ' ', 'X', ' ', 'X', ' '},
        {' ', 'X', ' ', 'X', ' ', 'X', ' ', 'X'},
        {'X', ' ', 'X', ' ', 'X', ' ', 'X', ' '},
        {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
        {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
        {'O', ' ', 'O', ' ', 'O', ' ', 'O', ' '},
        {' ', 'O', ' ', 'O', ' ', 'O', ' ', 'O'},
        {'O', ' ', 'O', ' ', 'O', ' ', 'O', ' '}
};
```
## Por implementar
- [X] Comprobar el jugador que va ganando
 - [ ] __Separar el programa en funciones__
     - [ ] _Contar negras_
   - [ ] _Contar blancas_
   - [ ] _Comprobar ganador_
- [ ] Movimiento de las fichas
- [ ] Damas reina (cuando una ficha llega al otro lado del tablero)
