# 📖 Repository Overview

This repository contains a collection of small, **pure‑HTML** demos that demonstrate various algorithms and features.  Each file is a self‑contained example that can be opened directly in a browser – no build tools, no node modules, no dependency hell.

## 📄 File List

| # | File | Lines | Size | Functions | Description |
|---|------|-------|------|----------|-------------|
| 1 | [blackjack.html](blackjack.html) | 135 | 3 KB | 8 | A simple Blackjack card game that shuffles a deck and manages player hands. |
| 2 | [bubble_sort_demo.html](bubble_sort_demo.html) | 71 | 2 KB | 3 | Visual bubble‑sort of numerical boxes. |
| 3 | [bubble_sort_demo2.html](bubble_sort_demo2.html) | 65 | 1.9 KB | 3 | Alternate bubble‑sort visualizer with different UI feedback. |
| 4 | [bubble_sort_demo3.html](bubble_sort_demo3.html) | 90 | 2.5 KB | 6 | Bubble‑sort of dynamic bar chart with swap animations. |
| 5 | [bubble_sort_demo4.html](bubble_sort_demo4.html) | 207 | 6.5 KB | 5 | Responsive bar‑chart bubble‑sort visualizer – works on small screens. |
| 6 | [bubble_sort_demo5.html](bubble_sort_demo5.html) | 74 | 2.7 KB | 4 | Bubble‑sort demo using a canvas for smoother animations. |
| 7 | [bubble_sort_demo6.html](bubble_sort_demo6.html) | 68 | 1.9 KB | 3 | Simple bubble‑sort visualisation with a log panel. |
| 8 | [bubble_sort_demo7.html](bubble_sort_demo7.html) | 114 | 3.0 KB | 3 | Bubble‑sort using color gradients for each element. |
| 9 | [color_picker.html](color_picker.html) | 42 | 1.3 KB | 1 | Classic color picker – pick colors from a wheel. |
|10 | [color_picker2.html](color_picker2.html) | 53 | 1.5 KB | 1 | Improved color picker with RGB sliders. |
|11 | [fire_effect.html](fire_effect.html) | 69 | 2.1 KB | 2 | Fire particle effect drawn on a canvas. |
|12 | [pong.html](pong.html) | 113 | 2.5 KB | 5 | Classic Pong game using canvas and keyboard controls. |
|13 | [rbtree_demo.html](rbtree_demo.html) | 268 | 7.8 KB | 6 | Visual binary search tree demo with insertion and traversal. |
|14 | [tic_tac_toe.html](tic_tac_toe.html) | 145 | 3.6 KB | 5 | Two‑player tic‑tac‑toe game with win/draw detection. |

---

## 📚 Full Guide

See the rest of this document for the guidelines on how to add new demos, coding conventions, contribution workflow, etc.

---

## ℹ️ About These demos

All demos are **tiny, isolated HTML files**.  They load instantly in the browser, run on all major browsers, and are ideal for educational purposes, code reviews, or quick visual tests.  If you want to add a new demo, simply create a new `.html` file with the same structure and update this `README.md`.

---

## 🚀 Getting Started

1. **Open any demo**
   ```bash
   # Windows
   start <demo>.html
   # macOS / Linux
   open <demo>.html
   ```
2. **Edit & refresh** – changes take effect instantly when you click, modify, and save.
3. **Add new demos** – follow the guidelines below.

---

## 📦 Adding a New Demo

1. Create a new HTML file with a clear descriptive name.
2. Use the **minimal template** below.
3. Keep it under 500 lines (≈10 KB).
4. Update this table and provide the functions count.
5. Commit and open a PR.

---

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Your Demo</title>
    <style><!-- optional scoped CSS --></style>
  </head>
  <body>
    <h1>Your Demo</h1>
    <script>
      // your JS
    </script>
  </body>
</html>
```

---

## 🛠️ Coding Standards

- **Vanilla JS** – no external libraries.
- **Strict mode** – `use strict` is implied.
- **No global pollution** – wrap code in functions or IIFEs.
- **Cross‑browser** – use standard DOM APIs.
- **Accessibility** – add `title` or `aria-` when using UI elements.

---

## 📌 How to Contribute

1. Fork the repo.
2. Add a new demo or improve an existing one.
3. Update the file table if you added a new file.
4. Push and open a pull request.

Happy hacking! 🚀
