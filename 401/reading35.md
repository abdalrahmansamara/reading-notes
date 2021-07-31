# graph

**The graph components :**
- Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
- Edge - An edge is a connection between two nodes.
- Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
- Degree - The degree of a vertex is the number of edges connected to that vertex.

An Undirected Graph is a graph where each edge is undirected or bi-directional. 

![image](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/UndirectedGraph.PNG)

**Directed Graphs :**
A Directed Graph also called a Digraph is a graph where every edge is directed , Digraph nodes has direction. Each node is directed at another node

![image](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DirectedGraph.PNG)

**types of graphs**

Complete Graphs : all nodes in the Complete Graphs  are connected 
Connected Graphs : all of nodes have at least one edge.
Disconnected Graphs : some nodes aren’t connected


An acyclic graph is a directed graph without cycles.

Graph Representation :
Adjacency Matrix : An Adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix
Adjacency List : An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

Traversals ways :
- Breadth First
- Depth First
