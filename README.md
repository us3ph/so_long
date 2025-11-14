# 🎮 So_Long – Pac-Man Style Game  

**A simple 2D Pac-Man inspired game built in C using MiniLibX.**

![C](https://img.shields.io/badge/Language-C-00599C?style=for-the-badge)
![MiniLibX](https://img.shields.io/badge/Graphics-MiniLibX-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

---

## 📌 Overview  
In **So_Long**, you control a player 😃 moving on a 2D map. Your goal:  

- Collect all items 🍒  
- Avoid obstacles 🟫  
- Reach the exit 🚪  

The project highlights:  
- 2D graphics with MiniLibX  
- Real-time movement and input handling  
- Map parsing and validation  
- Animation and game loop management  
- Modular, memory-safe C programming  

---

## ✨ Features  
- 🟢 Smooth player movement  
- 🟢 Collectibles and exit system  
- 🟢 Animated sprites for player and objects  
- 🟢 Custom `.ber` maps  
- 🟢 Flood-fill map validation  
- 🟢 Modular code structure  

---

## 🗂 Project Structure  
```
so_long/
│── animation.c          # Player & object animations
│── calculate.c          # Game calculations
│── count_and_store.c    # Map data management
│── drawing.c            # Rendering sprites
│── flood.c              # Map validation
│── freeing.c            # Memory cleanup
│── ft_split.c           # String splitting utility
│── get_next_line.c      # GNL implementation
│── get_next_line_utils.c
│── main.c               # Game entry point
│── moves.c              # Player movement
│── parsing.c            # Map parsing & validation
│── read_map.c           # Read map from file
│── update.c             # Game state updates
│── utils.c              # Helper functions
│── so_long.h            # Header file
│── ft_printf/           # printf utility
│── maps/                # Game maps
│── textures/            # Game textures
│── minilibx-linux/      # Graphics library
│── Makefile             # Build instructions
└── README.md
```

---

## 🕹 Controls  

| Action        | Key                  |
|---------------|--------------------|
| Move Up       | ↑ / W               |
| Move Down     | ↓ / S               |
| Move Left     | ← / A               |
| Move Right    | → / D               |

> Collect all 🍒 before reaching the exit 🚪 to win!

---

## 🎮 Mini Gameplay Diagram  

```
+-------------------+
| 🚪 Exit           |
| 🟫 Walls           |
| 🍒 Collectibles    |
| 😃 Player         |
+-------------------+
```

- Player moves through the maze  
- Collect all items  
- Exit unlocks when all collectibles are collected  

---

## 🚀 Installation

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/so_long.git
cd so_long
```

### 2️⃣ Build the project  
```bash
make
```

> This generates the `so_long` executable.

---

## ▶️ Usage

```bash
./so_long <map.ber>
```

- `<map.ber>` – Path to your custom `.ber` map  
- Example maps are included in `maps/`  

### Example  

```bash
./so_long maps/map1.ber
```

---

## 🧹 Cleanup  

Remove compiled binaries:

```bash
make fclean
```

---

## 📄 License  

This project is licensed under the **MIT License**.
