# Program README

## 1. Code Overview
The code is written in C++. It can be compiled in any C++ IDE.  
The code provides two shortest-distance algorithms (Dijkstra and Bellman-Ford) and compares their performance.

## 2. Input Data
The input file `input.txt` should be formatted as follows:

- The first line contains two integers: the number of nodes and edges in the graph.
- The following `m` lines each contain three integers: the starting node of an edge, the ending node of an edge(between 1 and n), the weight of the edge.(between -10000~10000)
- The final line specifies the source node.(between 1 and n)

## 3. Output Data

### `dijkstraoutput.txt`

This file contains the shortest path distances from the source node to each other node using Dijkstra's algorithm. If a node cannot be reached from the source node, it outputs a message `INF` instead of the distance. In addition, if there is even one negative-weight edge in the graph, it outputs a message `Edge with negative weight detected` instead of the result.


### `bellman-fordoutput.txt`

This file contains the shortest path distances from the source node to each other node using Bellman-Ford algorithm. If a node cannot be reached from the source node, it outputs a message `INF` instead of the distance. In addition, If a negative cycle is detected, it outputs a message `Negative cycle detected` instead of the result.


### `performance_comparison.txt`

This file compares the execution times of both algorithms. You can also check existence of negative edges or negative cycle in the graph.

## Author
- **NAME:** KANG TaeHyun
- **ID:** 2023-11127
