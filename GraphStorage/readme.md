# Graph Storage

Most graph computing algorithms assume that the adjacency matrix and adjacency lists can be stored in computer memory so the following 2 operations will
be fast:
* Is vertex v connected to vertex u?
* Produce a list of all vertices connected to v.

However, the advent of very large graphs (> 50,000,000 vertices and > 100,000,00) prevents the memory storage of the adjacency matrix and standard adjacency lists for these graphs. Design and implement in C++ a data structure for storing such graphs that is able to effectively perform the 2 operations listed above. 

## Solution
Use Disjoint Sets

## Usage
Compile and run

```bash
g++ main.cpp DisjointSet.cpp
./a.out

```
