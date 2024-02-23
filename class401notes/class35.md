# Graphs Cheat Sheet

Graphs are versatile data structures that model relationships between objects. They consist of vertices (nodes) and edges (lines connecting the vertices). Understanding graphs and their properties is crucial in computer science, mathematics, and various application domains.

## Basic Terminology

- **Vertex (Node):** A fundamental unit in a graph representing an object or a data point.
- **Edge:** A line connecting two vertices, indicating a relationship between them.
- **Neighbor:** Adjacent vertices connected directly by an edge.
- **Degree:** The number of edges connected to a vertex.
- **Directed Graph (Digraph):** A graph where edges have a direction, indicating the relationship's flow from one vertex to another.
- **Undirected Graph:** A graph where edges have no direction, implying a bidirectional relationship.

## Graph Types

- **Complete Graph:** Every vertex is connected to every other vertex.
- **Connected Graph:** There's at least one path between every pair of vertices.
- **Disconnected Graph:** At least one vertex is not connected to the others.

## Special Graphs

- **Acyclic Graph:** A graph with no cycles (a path where the first and last vertices are the same).
- **Cyclic Graph:** A graph that contains at least one cycle.
- **Weighted Graph:** A graph where edges have weights, representing the cost or distance between vertices.

## Graph Representations

- **Adjacency Matrix:** A 2D array where the cell at row i and column j indicates the presence (and possibly the weight) of an edge between vertices i and j.
- **Adjacency List:** A collection of lists or arrays where each list represents a vertex and contains the neighbors (and possibly the weights) of that vertex.

## Traversal Techniques

- **Breadth-First Search (BFS):** Starts at a specific vertex and explores its neighbors before moving on to the neighbors of those neighbors. Uses a queue to keep track of the order.
- **Depth-First Search (DFS):** Starts at a specific vertex and explores as far as possible along each branch before backtracking. Uses a stack or recursion.

## Real-World Applications

- **GPS and Mapping:** Finding the shortest paths between locations.
- **Social Networks:** Analyzing connections between individuals.
- **Airline Traffic:** Optimizing routes and schedules.
- **Content Recommendation:** Suggesting relevant content based on user preferences and connections.

