# Graph4 — Graph Algorithms in Java

A collection of **Graph Data Structure and Algorithm implementations in Java**, created as part of my Data Structures & Algorithms practice.

The repository focuses on implementing important graph algorithms from scratch and understanding their working, time complexity, and practical applications.

## 📌 Topics Covered

* Graph Representation
* Minimum Spanning Tree (MST)
* Prim's Algorithm
* Bellman-Ford Algorithm
* Shortest Path Algorithms
* Graph Traversal & Problem Solving

## 🛠️ Tech Stack

* **Language:** Java
* **Concept:** Data Structures & Algorithms
* **IDE:** IntelliJ IDEA / VS Code
* **Version Control:** Git & GitHub

## 📂 Files

| File                 | Description                                                            |
| -------------------- | ---------------------------------------------------------------------- |
| `MST_primsAlgo.java` | Implementation of Prim's Algorithm for finding a Minimum Spanning Tree |
| `bellmanFord.java`   | Implementation of the Bellman-Ford shortest path algorithm             |

## 🔹 Algorithms

### 1. Prim's Algorithm

Prim's Algorithm is a **greedy algorithm** used to find a Minimum Spanning Tree of a connected, weighted, undirected graph.

**Key idea:**

* Start from any vertex.
* Select the minimum-weight edge connecting the current MST to an unvisited vertex.
* Continue until all vertices are included.

**Complexity:**

Using an adjacency matrix:

```text
Time Complexity: O(V²)
```

Using a priority queue with an adjacency list:

```text
Time Complexity: O(E log V)
```

---

### 2. Bellman-Ford Algorithm

The Bellman-Ford algorithm finds the **shortest paths from a single source vertex** to all other vertices.

Unlike Dijkstra's algorithm, Bellman-Ford can handle graphs containing **negative edge weights**.

It can also detect **negative-weight cycles**.

**Complexity:**

```text
Time Complexity: O(V × E)
Space Complexity: O(V)
```

## 🎯 Learning Objectives

Through this repository, I am practicing:

* Graph representation
* Weighted graphs
* Minimum Spanning Trees
* Shortest path algorithms
* Greedy algorithms
* Relaxation technique
* Negative-weight edge handling
* Algorithmic complexity analysis
* Java implementation of DSA concepts

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/ujjawal808/Graph4.git
```

Navigate to the project:

```bash
cd Graph4
```

Compile a Java file:

```bash
javac MST_primsAlgo.java
```

Run it:

```bash
java MST_primsAlgo
```

For Bellman-Ford:

```bash
javac bellmanFord.java
java bellmanFord
```

## 📈 DSA Practice

This repository is part of my ongoing **Java + DSA practice**, where I am implementing data structures and algorithms to strengthen problem-solving and coding skills.

### Current Focus

* Graph Algorithms
* Trees & Binary Search Trees
* BFS & DFS
* Shortest Path Algorithms
* Dyna
