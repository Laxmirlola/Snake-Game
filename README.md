# 🐍 AI Snake Game

An intelligent Snake Game built using **Pygame**, enhanced with multiple **search algorithms**. Watch your AI snake navigate mazes, locate food, and grow — all by itself!

![image](https://github.com/user-attachments/assets/ebc14019-d713-4bfd-8144-dab2235dcf01)


---

## 🚀 Features

- 🧠 **AI-Powered Snake**: Navigates automatically using search algorithms.
- 🍎 **Food Hunting**: The snake finds and eats food to grow.
- ⛔ **Dynamic Obstacles**: Varying difficulty with different levels.
- 🕹️ **Interactive UI**: Clean visuals, live score, and timer.
- 🔁 **Replayable Levels**: Choose your challenge with increasing obstacle density.

---

## 🧠 Implemented Search Algorithms

| Algorithm     | Description                                 |
|--------------|---------------------------------------------|
| `random`     | Moves randomly (up to 1000 steps)           |
| `bfs`        | Breadth-First Search                        |
| `dfs`        | Depth-First Search                          |
| `ucs`        | Uniform Cost Search                         |
| `ids`        | Iterative Deepening Search                  |
| `greedy_bfs` | Greedy Best First Search                    |
| `astar`      | A* Search                                   |

---

## 🕹️ How to Play

### 1. 📦 Install Dependencies

```bash
pip install pygame
```

### 2. ▶️ Run the Game

```bash
python snake.py <level> <algorithm>
```

Example:
```bash
python snake.py level2 astar
```

---

## 🧩 Level Difficulty

| Level   | Obstacle Density |
|---------|------------------|
| level0  | No obstacles     |
| level1  | 5% filled        |
| level2  | 10% filled       |
| level3  | 15% filled       |

---

## 💡 Coming Soon

- 🎵 Sound effects & background music
- 🌈 Special food & power-ups
- 🐍 More realistic growing snake trail
- 🔍 Path animation for learning algorithms

---

## 🙋‍♂️ Author

**Laxmirlola Behera**  
[GitHub](https://github.com/Laxmirlola)
