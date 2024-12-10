**Transitive Closure Using Floyd-Warshall Algorithm**
This project implements the Transitive Closure of a directed graph using the Floyd-Warshall algorithm. The Floyd-Warshall algorithm is a dynamic programming technique used to find the shortest paths between all pairs of vertices in a weighted graph, and it can also be used to find the transitive closure of a graph.

**Overview**
In the context of graph theory, transitive closure is a way to compute whether there is a path between any two nodes in a directed graph. The Floyd-Warshall algorithm computes the transitive closure by iterating through all pairs of vertices and updating the reachability based on intermediate vertices.

**Features**
Implements the Floyd-Warshall algorithm for calculating the transitive closure.
Works for both weighted and unweighted directed graphs.
Outputs a reachability matrix indicating whether a path exists between any pair of vertices.
**How It Works**
Input Graph: The graph is represented as an adjacency matrix, where the matrix entry graph[i][j] is 1 if there is a directed edge from node i to node j, and 0 otherwise.
Floyd-Warshall Algorithm: The algorithm updates the reachability of nodes by checking for paths through intermediate vertices.
Output: The result is a transitive closure matrix that indicates which nodes are reachable from others.
