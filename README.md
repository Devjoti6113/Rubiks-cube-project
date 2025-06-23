# 🧊 Rubik’s Cube Solver in C++

A modular and efficient **Rubik’s Cube Solver** implemented in **C++**, using classical and advanced search algorithms like **BFS**, **DFS**, **IDDFS**, and **Korf’s IDA\***. Designed with clean object-oriented architecture and built using **CMake** for easy compilation and maintainability.

---

## 🚀 Features

- Full 3x3 Rubik’s Cube simulation with move logic
- Implemented multiple solving algorithms and compared their performance
- Structured using modular C++ classes (`Model/`, `Solver/`)
- Efficient cube state encoding and rotation mapping
- Easily portable and buildable using `CMake`

---

## 🧠 Algorithms Used

- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS)**
- **Iterative Deepening DFS (IDDFS)**
- **Korf’s IDA\*** (Iterative Deepening A\* with heuristics)

---

## 📁 Project Structure

Rubiks-cube-project/
├── Model/ # Cube representation & state logic
├── Solver/ # Solving algorithms
├── main.cpp # Entry point
├── CMakeLists.txt # CMake build script
└── README.md


---

## ⚙️ Build & Run Instructions

### Prerequisites
- `g++` with C++17 support
- `cmake` version 3.10 or higher

### Steps

```bash
git clone https://github.com/Devjoti6113/Rubiks-cube-project.git
cd Rubiks-cube-project
mkdir build && cd build
cmake ..
make
./RubiksCubeSolver
```

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Korf, R.E., “Finding Optimal Solutions to Rubik’s Cube Using Pattern Databases”

Open-source contributions and C++ STL community

📫 Contact
GitHub: Devjoti6113
