# test-for-coder
A small collection of simple web examples created for experimenting with the Coder terminal AI.

## Files

| File | Lines | Characters (≈) | JavaScript functions |
|------|-------|----------------|---------------------|
| `color_picker.html` | 43 | ≈ 1 450 | 1 (`randomColor`) |
| `color_picker2.html` | 53 | ≈ 1 200 | 2 (`getRandomColor`, event handler) |
| `tic_tac_toe.html` | 146 | ≈ 5 040 | 5 (`updateStatus`, `checkWin`, `checkDraw`, `handleCellClick`, `resetGame`) |
| `pong.html` | 111 | ≈ 3 200 | 5 (`drawNet`, `drawRect`, `drawCircle`, `draw`, `resetBall`) |
| `blackjack.html` | 136 | ≈ 4 000 | 8 (`createDeck`, `shuffle`, `cardValue`, `handValue`, `drawCard`, `renderHand`, `startGame`, `updateMessage`) |
| `bubble_sort_demo2.html` | 72 | ≈ 4 200 | 4 (`bubbleSort`, `createBoxes`, `log`, `sortBtn`) |
| `bubble_sort_demo3.html` | 88 | ≈ 5 200 | 6 (`generateSteps`, `renderArray`, `activeClass`, `nextStep`, `playSteps`, `sortBtn`) |
| `bubble_sort_demo4.html` | 74 | ≈ 3 900 | 5 (`drawBars`, `generateArray`, `playVisualization`, `sortBtn`, `resetBtn`) |
| `bubble_sort_demo5.html` | 75 | ≈ 3 300 | 4 (`renderArray`, `getRandomArray`, `sleep`, `bubbleSort`) |
| `bubble_sort_demo6.html` | 69 | ≈ 4 000 | 3 (`render`, `bubbleSort`, `createArray`) |
| `rbtree_demo.html` | 23 | ≈ 1 250 | 1 (`draw`) |
| **`fire_effect.html`** | 70 | ≈ 2 100 | 2 (`step`, `render`) |

## Total
**960**
**≈ 38 840**
**38**

## Game Descriptions
- **color_picker.html**: Randomly pick a color and change the page background.
- **color_picker2.html**: Improved color picker with button‑colored text.
- **tic_tac_toe.html**: Simple two‑player Tic‑Tac‑Toe with win/draw detection.
- **pong.html**: A simple Pong game with two paddles and a ball.
- **blackjack.html**: Simple Blackjack game with hit and stand options.
- **bubble_sort_demo2.html**: A minimal span‑box bubble sort visualization with background highlighting.
- **bubble_sort_demo3.html**: A step‑buffered box‑block bubble sort visualization separated into data and animation layers.
- **bubble_sort_demo4.html**: A responsive bar‑chart bubble sort visualizer with color highlights and disabled controls.
- **bubble_sort_demo5.html**: A quick‑sort style bubble sort with 2‑D bars and async step animation.
- **bubble_sort_demo6.html**: A dynamic bar‑chart bubble sort visualizer with shuffle and sort controls; uses async delays for animation.
- **rbtree_demo.html**: A simple Red‑Black Tree visualizer placeholder.
- **fire_effect.html**: Real‑time ASCII “fire” effect rendered in a `<pre>` element, demonstrating a lightweight particle‑like simulation without a canvas.

## How to Run

Because they are plain HTML files you can simply open them in a browser:

```bash
# Windows
start color_picker.html
start tic_tac_toe.html
start pong.html
start blackjack.html
start bubble_sort_demo2.html
start bubble_sort_demo3.html
start bubble_sort_demo4.html
start bubble_sort_demo5.html
start bubble_sort_demo6.html
start rbtree_demo.html
start fire_effect.html
```

or double‑click them in Explorer. No server or build step is required.

## Extending

You can extend the examples further or create new ones by following the same structure.