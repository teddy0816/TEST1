# Program README

## 1. Code Overview
The code is written in C++. It can be compiled in any C++ IDE.  
The code provides three MST algorithms (Kruskal's, Prim's, and Prim's with fibonacci heap) and compares their performance.

## 2. Input Data
The input file `input.txt` should be formatted as follows:

- The first line contains two integers: the number of nodes and edges in the graph.
- The following `m` lines each contain three integers: the starting node of an edge, the ending node of an edge(between 1 and n), the weight of the edge.(between -10000~10000)

## 3. Output Data

### `kruskal_mst.txt`, `prim_mst.txt`, `prim_fib_heap_mst.txt`

This file contains information of MST for given graph. The first line of file means total cost of MST. Following lines(Form : a b c) show how MST composed, Third unit of each line(c) means whether the edge connect a and b contained in MST(c=1 or c=0)

### `timingdata.txt`

This file compares the execution times of algorithms.

## Author
- **NAME:** KANG TaeHyun
- **ID:** 2023-11127
