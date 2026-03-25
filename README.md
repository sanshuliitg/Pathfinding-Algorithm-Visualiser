# Pathfinding Algorithm Visualiser

A dynamic pathfinding visualizer built with React.js that implements graph traversal algorithms to compute and animate optimal paths in real time. This project features a high-performance visualization engine using asynchronous JavaScript and direct DOM manipulation to deliver smooth algorithm exploration while avoiding expensive React re-renders.

## Features

- **Multiple Graph Traversal Algorithms**: Visualize Dijkstra's shortest path, A\* pathfinding, and Breadth-First Search (BFS) algorithms in real time.
- **Interactive Grid System**: Event-driven state management enables users to dynamically create custom layouts, place walls, and configure start/target nodes.
- **High-Performance Rendering**: Optimized visualization engine using asynchronous JavaScript and direct DOM manipulation for smooth animation and efficient rendering.
- **Algorithm Efficiency Evaluation**: Observe and compare how different algorithms explore the grid and compute optimal paths.
- **Custom Maze Creation**: Interactively draw walls and obstacles by clicking and dragging across the grid.

## Technical Highlights

- **Performance-Optimized Architecture**: Leverages asynchronous JavaScript patterns and direct DOM manipulation to render smooth algorithm exploration while avoiding expensive React re-renders.
- **Event-Driven State Management**: Custom state management system enables efficient real-time updates and responsive user interactions.
- **Algorithm Implementations**: Clean, optimized implementations of Dijkstra's, A\*, and BFS algorithms with animated path exploration.

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

## Usage

### Interacting with the Grid

- **Create Walls**: Click and drag on the grid to draw walls and obstacles.
- **Reposition Nodes**: Click and drag the start (green) or end (red) nodes to configure custom start/target positions.
- **Create Custom Layouts**: Build any maze configuration by combining walls and node placement to test algorithm efficiency.

### Visualizing Algorithms

1. **Select Algorithm**: Choose from Dijkstra's, A\*, or BFS using the dropdown menu.
2. **Run Visualization**: Click the "Visualize Algorithm" button to execute the algorithm and animate the path exploration in real time.

## Project Structure

- **src/PathfindingVisualizer**: Main visualizer component and related logic.
- **src/algorithms**: Pathfinding algorithm implementations.
- **src/Node**: Node component representing each grid cell.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sanshuliitg/Pathfinding-Algorithm-Visualiser.git
   cd Pathfinding-Algorithm-Visualiser
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.

## Acknowledgements

- [React](https://reactjs.org/)
- [Dijkstra's Algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
- [A\* Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)
- [Breadth-First Search (BFS)](https://en.wikipedia.org/wiki/Breadth-first_search)
