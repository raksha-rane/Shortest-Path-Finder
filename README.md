# Shortest Path Finder

## Overview

**Shortest Path Finder** is an interactive web application built using React.js and Node.js to visually demonstrate the implementation of Dijkstra's algorithm. The tool allows users to find the shortest path between two points on a grid. Users can dynamically add obstacles (barriers) that influence the pathfinding process, providing a hands-on experience with graph theory and shortest path algorithms.

## Features

- **Dynamic Grid Manipulation**: Users can interactively create a grid, specify start and end points, and add barriers to simulate obstacles, making the pathfinding problem more realistic.
- **Dijkstra’s Algorithm**: The core pathfinding logic is based on Dijkstra's algorithm, which dynamically calculates the shortest path between the start and end points.
- **Real-Time Visualisation**: The grid dynamically updates to show the algorithm's progress, including the exploration of nodes and the final shortest path.
- **Interactive Controls**: Reset the grid, change start and end points, or add/remove obstacles to see how the algorithm adapts.
- **Practical Applications**: Demonstrates real-world applications of Dijkstra’s algorithm in areas such as network routing and navigation systems.

## Technologies Used

- **React.js**: Used for building the dynamic and interactive front-end, handling user interactions, and rendering the grid.
- **Node.js**: Implements server-side logic and handles the computations for Dijkstra’s algorithm.
- **CSS**: For styling the grid and creating visual animations.
- **JavaScript**: For implementing Dijkstra’s algorithm and managing data structures and the pathfinding process.

## Algorithm Explanation

- **Dijkstra’s Algorithm**: 
  - **Initialization**: Each node is assigned a tentative distance, with the start node set to 0 and all others set to infinity.
  - **Processing**: The algorithm processes the node with the smallest tentative distance, marks it as visited, and updates the distances of its neighboring nodes.
  - **Completion**: This process continues until all nodes are visited, or the shortest path is found.
  
The progress is visualized on the grid, with different colors indicating explored nodes, nodes being processed, and the final path.

## Data Structures Used

- **Priority Queue (Min-Heap)**: Efficiently selects the next node with the smallest tentative distance for processing.
- **Adjacency List**: Represents the graph where each node points to its neighbors and the edge weights.
- **2D Array (Grid)**: The grid is a 2D array where each cell is a node, and the algorithm operates on this structure.

## Setup Instructions

### Prerequisites
- **Node.js** and **npm** installed on your machine.
- Basic knowledge of React.js and Node.js is recommended.

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/shortest-path-finder.git
    ```

2. Navigate to the project directory:
    ```bash
    cd shortest-path-finder
    ```

3. Install dependencies for both the client and server:
    ```bash
    npm install
    ```

4. Start the React development server:
    ```bash
    npm start
    ```

5. The application should now be running at `http://localhost:3000`.

### Usage

- Open the app in your browser.
- Define the start and end points on the grid.
- Add barriers to simulate obstacles.
- Watch the visual representation of Dijkstra’s algorithm in real-time as it finds the shortest path.
- Reset the grid and experiment with different configurations.

## Future Enhancements

- Support for other pathfinding algorithms like A* and BFS.
- Enhanced visual feedback with more customization options for users.
- Option to save and load custom grid configurations.

