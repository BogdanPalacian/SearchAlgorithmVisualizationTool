# 🔍 Path-Finding Algorithm Visualization

A simple and interactive tool for visualizing common search algorithms on a grid. Watch in real-time how different algorithms find their way from start to end points!


## 📋 Overview

This project provides a visual representation of how various path-finding algorithms work. The algorithms implemented include:

- **A\* Search Algorithm** - Combines features of Dijkstra's and Greedy Best-First Search using a heuristic
- **Breadth-First Search (BFS)** - Explores all neighbors at the present depth before moving to nodes at the next depth level
- **Depth-First Search (DFS)** - Explores as far as possible along each branch before backtracking
- **Dijkstra's Algorithm** - Finds the shortest path between nodes in a graph
- **Uniform Cost Search** - Similar to Dijkstra's algorithm for this grid implementation

The visualization makes it easy to understand how these algorithms traverse a space and find (or fail to find) a path between two points.

## 🚀 Setup Instructions

### Prerequisites

- ✅ Python 3.x installed
- ✅ Pygame library installed

### Installation Steps

1. 📥 **Clone or download** this repository to your local machine
2. 🐍 **Install Pygame** (if you haven't already):
   ```
   pip install pygame
   ```
3. 🏃‍♂️ **Run the program**:
   ```
   python AlgorithmVisualization.py
   ```

## 🎮 How to Use

### Basic Controls

- **Left Mouse Button**: 
  - First click: Set start point (orange)
  - Second click: Set end point (turquoise)
  - Additional clicks: Create barriers (black)

- **Right Mouse Button**:
  - Remove/reset any point or barrier

- **Keyboard**:
  - `A`: Run A* algorithm
  - `B`: Run Breadth-First Search (BFS)
  - `D`: Run Depth-First Search (DFS)
  - `J`: Run Dijkstra's algorithm
  - `U`: Run Uniform Cost Search
  - `C`: Clear the grid and reset

### Step-by-Step Usage

1. 🟠 Set a **start point** with your first left click
2. 🔷 Set an **end point** with your second left click
3. 🧱 Create **barriers** by clicking additional spots on the grid
4. 🔑 Press one of the algorithm keys to start the visualization
5. 🔄 Press `C` to clear the grid and start over

## 🎨 Color Guide

- **Orange**: Start point
- **Turquoise**: End point
- **Black**: Barriers/walls
- **Red**: Visited nodes
- **Green**: Nodes currently in the open set
- **Purple**: Final path
- **White**: Unvisited nodes

## 📊 Algorithm Comparisons

### A* Search
- Typically finds the shortest path
- Uses a heuristic to guide the search
- Generally more efficient than Dijkstra's for pathfinding

### BFS
- Always finds the shortest path in unweighted graphs
- Explores equally in all directions
- Can be inefficient for large spaces

### DFS
- May not find the shortest path
- Memory efficient
- Can get stuck in deep branches

### Dijkstra's Algorithm
- Always finds the shortest path
- Explores based on accumulated cost
- Slower than A* when a good heuristic is available

## 🛠️ Technical Details

- Grid size: 50x50 cells
- Window size: 800x800 pixels
- Built with Python and Pygame


---
