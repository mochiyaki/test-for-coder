   1: # test-for-coder
   2: 
   3: A small collection of simple web examples created for experimenting with the Coder terminal AI.
   4: 
   5: ## Files
   6: 
   7: | File | Lines | Characters (≈) | JavaScript functions |
   8: |------|-------|----------------|---------------------|
   9: | `color_picker.html` | 43 | ≈ 1 450 | 1 (`randomColor`) |
  10: | `tic_tac_toe.html` | 146 | ≈ 5 040 | 5 (`updateStatus`, `checkWin`, `checkDraw`, `handleCellClick`, `resetGame`) |
  11: | `pong.html` | 111 | ≈ 3 200 | 5 (`drawNet`, `drawRect`, `drawCircle`, `draw`, `resetBall`) |
  12: | `blackjack.html` | 136 | ≈ 4 000 | 8 (`createDeck`, `shuffle`, `cardValue`, `handValue`, `drawCard`, `renderHand`, `startGame`, `updateMessage`) |
  13: | `bubble_sort_demo2.html` | 72 | ≈ 4 200 | 4 (`bubbleSort`, `createBoxes`, `log`, `sortBtn`) |
  14: | `bubble_sort_demo3.html` | 88 | ≈ 5 200 | 6 (`generateSteps`, `renderArray`, `activeClass`, `nextStep`, `playSteps`, `sortBtn`) |
  15: | `bubble_sort_demo4.html` | 74 | ≈ 3 900 | 5 (`drawBars`, `generateArray`, `playVisualization`, `sortBtn`, `resetBtn`) |
  16: | `rbtree_demo.html` | 23 | ≈ 1 250 | 1 (`draw`) |
  17: | **Total** | **693** | **≈ 28 240** | **35** |
  18: 
  19: ## Game Descriptions
  20: 
  21: - **color_picker.html**: Randomly pick a color and change the page background.
  22: - **tic_tac_toe.html**: Simple two‑player Tic‑Tac‑Toe with win/draw detection.
  23: - **pong.html**: A simple Pong game with two paddles and a ball.
  24: - **blackjack.html**: Simple Blackjack game with hit and stand options.
  25: - **bubble_sort_demo2.html**: A minimal span‑box bubble sort visualization with background highlighting.
  26: - **bubble_sort_demo3.html**: A step‑buffered box‑block bubble sort visualization separated into data and animation layers.
  27: - **bubble_sort_demo4.html**: A responsive bar‑chart bubble sort visualizer with color highlights and disabled controls.
  28: - **rbtree_demo.html**: A simple Red‑Black Tree visualizer placeholder.
  29: 
  30: ## How to Run
  31: 
  32: Because they are plain HTML files you can simply open them in a browser:
  33: 
  34: ```bash
  35: # Windows
  36: start color_picker.html
  37: start tic_tac_toe.html
  38: start pong.html
  39: start blackjack.html
  40: start bubble_sort_demo2.html
  41: start bubble_sort_demo3.html
  42: start bubble_sort_demo4.html
  43: start rbtree_demo.html
  44: ```
  45: 
  46: or double‑click them in Explorer. No server or build step is required.
  47: 
  48: ## Extending
  49: 
  50: Feel free to add more examples or convert the existing ones into a single page. The scripts are written to be self‑contained.
  51: 
  52: ---
  53: 
  54: **Enjoy experimenting!**