# AI Search Algorithms

This repository provides implementations and explanations for various AI search algorithms learned and Implemented over the period of the Artificial Intelligence Course

## Breadth-First Search (BFS)

Breadth-First Search is an algorithm that explores all the vertices of a graph or nodes of a tree in breadthward motion. It starts at the tree root (or some arbitrary node of the graph) and explores the neighbor nodes at the present depth prior to moving on to nodes at the next depth level.

**Time Complexity:**
- Worst-case: O(|V| + |E|), where |V| is the number of vertices and |E| is the number of edges.

## Depth-First Search (DFS)

Depth-First Search is an algorithm that explores a graph or tree by going as far as possible along each branch before backtracking. It starts at the tree root (or some arbitrary node of the graph) and explores as far as possible along each branch before backtracking.

**Time Complexity:**
- Worst-case: O(|V| + |E|), where |V| is the number of vertices and |E| is the number of edges.

## Uniform Cost Search (UCS)

Uniform Cost Search is a variant of Dijkstra's algorithm that finds the path with the minimum cost in a weighted graph. It explores the paths in increasing order of cost.

**Time Complexity:**
- Worst-case: O((|E| + |V|) log |V|), where |V| is the number of vertices and |E| is the number of edges.

## Iterative Deepening Search (IDS)

Iterative Deepening Search is a combination of depth-first search and breadth-first search algorithms. It repeatedly increases the depth limit of the search until the goal is found.

**Time Complexity:**
- Worst-case: O(|V| * |E|), where |V| is the number of vertices and |E| is the number of edges.

## Heuristic Search

Heuristic Search algorithms use heuristics to improve the efficiency of the search. A heuristic is a function that provides an estimate of the cost to reach the goal.

## Hill Climbing

Hill Climbing is a local search algorithm that continuously moves towards the direction of increasing elevation (improvement) to find the peak of the mountain (optimal solution).

**Time Complexity:**
- Worst-case: O(infinite) in some cases, as it may not always converge.

## Simulated Annealing

Simulated Annealing is a probabilistic optimization algorithm inspired by the annealing process in metallurgy. It allows the algorithm to accept worse solutions with a decreasing probability, avoiding local optima.

**Time Complexity:**
- Depends on the specific implementation and problem.

Feel free to explore the implementations in the repository for a hands-on understanding of these algorithms.

