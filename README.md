# 2048 Clone

![Preview](preview.png)

A smooth and satisfying 2048 game made in Java 8 using Processing.  
Everything's animated — tiles slide, merge, and hover nicely. You can change the board size, reset whenever, and it just works.

---

## ✨ Features

- Fully working 2048 gameplay
- Smooth tile movement and merging
- All tiles are rendered with images (no text or rectangles)
- Hover effects when your mouse is over empty cells
- Timer in the top-right corner
- Press `R` to reset the game anytime
- Works with different board sizes like 5x5 or 6x6

---

## 🚀 Running the Game

You’ll need Java 8 and either Gradle installed — or just use the Gradle wrapper that comes with the project.

```bash
# Default 4x4 board
./gradlew run

# Or run with a custom grid size (e.g. 5x5)
./gradlew run --args="5"