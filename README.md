# Snake Game
## Cómo jugar

1. Abre el archivo `index.html` directamente en tu navegador
2. Presiona **INICIAR** para comenzar
3. Usa las **teclas de flecha** para mover la serpiente:
   - `↑` — arriba
   - `↓` — abajo
   - `←` — izquierda
   - `→` — derecha
4. Come la comida (cuadro rojo) para crecer y sumar puntos
5. Evita chocar contigo mismo — el juego termina si lo haces
6. Al cruzar un borde, la serpiente aparece por el lado opuesto
7. Cuando pierdes, presiona **REINICIAR** para jugar de nuevo

## Componentes

| Componente | Descripción |
|------------|-------------|
| `Game`     | Contenedor principal, maneja todo el estado y la lógica |
| `Board`    | Tablero de juego (grid 15×15) |
| `Snake`    | Renderiza los segmentos de la serpiente |
| `Segment`  | Un cuadro individual de la serpiente |
| `Food`     | La comida que aparece en el tablero |
| `Score`    | Muestra el puntaje actual |
| `Overlay`  | Pantalla de inicio y de game over |

## Tecnologías

- React 18 (CDN)
- Babel Standalone (CDN)
- HTML / CSS 
