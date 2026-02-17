# 2048 Mini Game

A classic **2048**-style puzzle game built with **Python** and **Pygame**. Slide numbered tiles on a 4×4 grid and combine them to reach the 2048 tile—and beyond.

![Python](https://img.shields.io/badge/python-3.7+-blue.svg)
![Pygame](https://img.shields.io/badge/pygame-2.0+-green.svg)

---

## Screenshot

*Run the game to see the 4×4 grid with smooth tile rendering and a clean, modern look.*

---

## Features

- **4×4 grid** — Classic 2048 board layout
- **Smooth visuals** — Color-coded tiles and clear grid lines
- **Pygame-based** — Cross-platform desktop game with 60 FPS
- **Simple setup** — Single main script, minimal dependencies

---

## Requirements

- **Python** 3.7 or higher  
- **Pygame** 2.0 or higher  

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/2048-mini-game.git
   cd 2048-mini-game
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run

From the project root:

```bash
python 2048.py
```

A 640×640 game window will open. Use the window controls to close the game when done.

---

## Project Structure

```
2048-mini-game/
├── 2048.py          # Main game logic and Pygame entry point
├── requirements.txt # Python dependencies
└── README.md        # This file
```

---

## Controls

| Action   | Input        |
|----------|--------------|
| Move     | Arrow keys   |
| Quit     | Close window |

---

## How It Works

- The game starts with two tiles of value **2** in random cells.
- Tiles are drawn with colors that depend on their value (2, 4, 8, …).
- The grid is rendered with a subtle outline and background for a clean board.

---

## License

This project is open source. Feel free to use and modify it for learning or fun.

---

## Contributing

Contributions are welcome. Open an issue or submit a pull request if you have ideas or improvements.
