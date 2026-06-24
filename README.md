# Romania Map IDDFS Search Visualizer

An interactive Python application that demonstrates the **Iterative Deepening Depth-First Search (IDDFS)** algorithm on the classic Romania Road Map problem from Artificial Intelligence.

The project provides a graphical visualization of how IDDFS explores nodes, backtracks, increases depth limits, and eventually finds the optimal path between two cities.

---

## Features

- Interactive GUI built with Tkinter
- Visualization of the Romania Road Map
- User-selectable source and destination cities
- Adjustable animation speed
- Real-time display of:
  - Node exploration
  - Backtracking
  - Depth limit increments
  - Final solution path
- Color-coded search states for better understanding

---

## Concepts Demonstrated

- Graph Representation
- Iterative Deepening Depth-First Search (IDDFS)
- Depth-Limited Search (DLS)
- Recursive Search Algorithms
- Pathfinding in Graphs
- GUI Development using Tkinter
- Search Algorithm Visualization

---

## Technologies Used

- Python
- Tkinter
- Threading
- Graph Search Algorithms

---

## Project Structure

```
.
├── AI_IDDFS.py
├── README.md
└── .gitignore
```

---

## Romania Map Problem

The application uses the famous Romania Road Map problem commonly found in Artificial Intelligence textbooks.

The objective is to find a path between a selected source city and destination city using the IDDFS algorithm.

---

## How IDDFS Works

Iterative Deepening Depth-First Search combines the advantages of:

- Depth-First Search (low memory usage)
- Breadth-First Search (completeness)

The algorithm repeatedly performs Depth-Limited Search with increasing depth limits until the goal node is found.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/romania-map-iddfs-visualizer.git
```

Navigate to the project directory:

```bash
cd romania-map-iddfs-visualizer
```

---

## Run the Application

```bash
python AI_IDDFS.py
```

---

## Usage

1. Select a Source City.
2. Select a Destination City.
3. Adjust the animation speed if desired.
4. Click **SUBMIT**.
5. Observe:
   - Search progression
   - Node visits
   - Backtracking
   - Depth increments
   - Final solution path

---

## Color Legend

| Color | Meaning |
|---------|---------|
| Green | Source Node |
| Red | Destination Node |
| Yellow | Currently Visiting |
| Purple | Current Search Path |
| Dark Gray | Dead End / Backtracked |
| Blue | Final Solution Path |

---

## Learning Outcomes

This project helps understand:

- How IDDFS works internally
- Search tree expansion
- Recursive graph traversal
- Backtracking mechanisms
- AI search strategies

---

## Future Improvements

- Add BFS Visualization
- Add DFS Visualization
- Add Uniform Cost Search
- Add A* Search Algorithm
- Display path cost calculations
- Support custom graphs

---

## Author
kimayayaya
