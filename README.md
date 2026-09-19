# 🚀 Graph4 — Java Graph Algorithms & DSA

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=java" alt="Java"/>
  <img src="https://img.shields.io/badge/DSA-Graph%20Algorithms-blue?style=for-the-badge" alt="DSA"/>
  <img src="https://img.shields.io/badge/Algorithms-MST%20%7C%20Shortest%20Path-green?style=for-the-badge" alt="Algorithms"/>
  <img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" alt="GitHub"/>
</p>

<p align="center">
  <b>Implementation of important Graph Data Structures and Algorithms using Java.</b>
</p>

---

## 👨‍💻 About Me

Hi, I'm **Ujjawal Baliyan**, an MCA student passionate about **Software Development, Data Structures & Algorithms, and Problem Solving**.

I use Java to strengthen my understanding of DSA by implementing algorithms from scratch and solving programming problems.

This repository is part of my ongoing **Java DSA learning journey**, focusing specifically on Graph algorithms.

---

## 🎯 What I Bring

* 💻 Strong foundation in **Java**
* 🧠 Problem-solving and algorithmic thinking
* 🌳 Data Structures & Algorithms practice
* 📊 Graph algorithm implementation
* 🔍 Understanding of time and space complexity
* 🛠️ Hands-on coding practice
* 🚀 Continuous learning and improvement

---

## 🧰 Tech Stack

### Programming Language

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
</p>

### Core Concepts

```text
Data Structures
Algorithms
Graph Theory
Greedy Algorithms
Shortest Path Algorithms
Minimum Spanning Tree
Priority Queue
Adjacency List
Weighted Graphs
```

### Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
</p>

---

# 📚 Graph Algorithms Covered

This repository contains implementations of important graph algorithms including:

* 🔗 Graph Representation
* 🌲 Minimum Spanning Tree
* ⚡ Prim's Algorithm
* 🛣️ Bellman-Ford Algorithm
* 📍 Single Source Shortest Path
* 🔄 Edge Relaxation
* ⚠️ Negative Weight Cycle Detection
* 🧮 Weighted Graph Problems

---

# 📂 Project Structure

```text
Graph4/
│
├── MST_primsAlgo.java
├── bellmanFord.java
└── README.md
```

---

# 🔥 Featured Implementations

## 🌲 1. Prim's Algorithm

**File:** `MST_primsAlgo.java`

Prim's Algorithm is a **greedy algorithm** used to find the **Minimum Spanning Tree (MST)** of a connected, weighted, undirected graph.

### 💡 Key Concept

The algorithm starts from a vertex and repeatedly selects the minimum-weight edge that connects a vertex already present in the MST to a vertex outside the MST.

### 🔄 General Approach

```text
Start from a source vertex
        ↓
Select minimum weight edge
        ↓
Add new vertex to MST
        ↓
Update available edges
        ↓
Repeat until all vertices are included
```

### ⏱️ Complexity

Using a Priority Queue and adjacency list:

```text
Time Complexity  : O(E log V)
Space Complexity : O(V + E)
```

---

# ⚡ 2. Bellman-Ford Algorithm

**File:** `bellmanFord.java`

Bellman-Ford is a **single-source shortest path algorithm** that calculates the shortest distance from a source vertex to all other vertices.

One of its important advantages is that it can work with **negative edge weights**.

It can also detect the presence of a **negative-weight cycle**.

### 💡 Key Concept

The algorithm repeatedly relaxes every edge.

For an edge:

```text
u → v
```

with weight `w`, the relaxation condition is:

```text
distance[v] > distance[u] + w
```

If true:

```text
distance[v] = distance[u] + w
```

### 🔄 General Approach

```text
Initialize distances
        ↓
Set source distance = 0
        ↓
Relax all edges V - 1 times
        ↓
Check edges one more time
        ↓
Negative cycle detected?
        ↓
Print shortest distances
```

### ⏱️ Complexity

```text
Time Complexity  : O(V × E)
Space Complexity : O(V)
```

---

# 🧠 Important Graph Concepts

### Graph

A graph consists of:

```text
Vertices (Nodes)
        +
Edges (Connections)
```

Graphs can be:

* Directed
* Undirected
* Weighted
* Unweighted
* Cyclic
* Acyclic
* Connected
* Disconnected

---

## 🌲 Minimum Spanning Tree

A Minimum Spanning Tree is a spanning tree of a connected weighted undirected graph with the minimum possible total edge weight.

Important MST algorithms:

```text
Prim's Algorithm
Kruskal's Algorithm
```

---

## 📍 Shortest Path

Shortest path algorithms are used to find minimum-cost paths between vertices.

Important algorithms include:

```text
BFS
Dijkstra
Bellman-Ford
Floyd-Warshall
```

---

# 📊 Algorithm Comparison

| Algorithm    | Purpose                           | Negative Edges | Negative Cycle Detection |
| ------------ | --------------------------------- | -------------: | -----------------------: |
| BFS          | Shortest path in unweighted graph |              ❌ |                        ❌ |
| Dijkstra     | Shortest path                     |              ❌ |                        ❌ |
| Bellman-Ford | Shortest path                     |              ✅ |                        ✅ |
| Prim's       | Minimum Spanning Tree             |            N/A |                      N/A |
| Kruskal's    | Minimum Spanning Tree             |            N/A |                      N/A |

---

# 🎓 Learning Objectives

Through this repository, I am improving my understanding of:

* Graph representation
* Weighted graphs
* Graph traversal
* Minimum Spanning Trees
* Shortest path algorithms
* Greedy algorithms
* Edge relaxation
* Negative edge weights
* Negative cycle detection
* Priority Queues
* Time & Space Complexity
* Java implementation of algorithms

---

# 💻 DSA Journey

This repository is part of my broader **Java + DSA practice journey**.

### Topics Practiced

```text
✅ Arrays
✅ Strings
✅ Linked Lists
✅ Stack
✅ Queue
✅ Binary Trees
✅ Binary Search Trees
✅ Graphs
🔄 Dynamic Programming
🔄 Advanced Graph Algorithms
```

---

# 🧩 Problem-Solving Approach

For every algorithm, I focus on:

```text
1. Understand the problem
        ↓
2. Identify the appropriate data structure
        ↓
3. Understand the algorithm
        ↓
4. Implement it in Java
        ↓
5. Analyze Time Complexity
        ↓
6. Analyze Space Complexity
        ↓
7. Test with different inputs
```

---

# 📈 Current Focus

Currently focusing on:

* 🧠 Advanced DSA
* ☕ Java Problem Solving
* 🌐 Graph Algorithms
* 🌲 Trees
* ⚡ Dynamic Programming
* 💻 LeetCode Problems
* 🎯 Placement Preparation
* 🚀 Software Engineering Fundamentals

---

# 🏆 DSA Goals

My current goals include:

* Solve more **DSA problems**
* Improve problem-solving speed
* Master Graph algorithms
* Strengthen Java fundamentals
* Prepare for technical interviews
* Build efficient and optimized solutions
* Improve competitive programming skills

---

# 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ujjawal808&show_icons=true&theme=tokyonight&hide_border=true" height="180"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ujjawal808&layout=compact&theme=tokyonight&hide_border=true" height="180"/>
</p>

---

# 🔥 GitHub Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ujjawal808&theme=tokyonight&hide_border=true" />
</p>

---

# 🧑‍💻 Developer Journey

```text
Learning
   ↓
Understanding
   ↓
Implementation
   ↓
Problem Solving
   ↓
Optimization
   ↓
Interview Preparation
   ↓
Software Engineer 🚀
```

I believe consistent practice and understanding the fundamentals are the keys to becoming a strong software developer.

---

# 📌 Future Improvements

Planned additions to this repository:

* [ ] BFS
* [ ] DFS
* [ ] Dijkstra's Algorithm
* [ ] Kruskal's Algorithm
* [ ] Topological Sort
* [ ] Cycle Detection
* [ ] Disjoint Set Union
* [ ] Floyd-Warshall Algorithm
* [ ] Strongly Connected Components
* [ ] Advanced Graph Problems
* [ ] More interview-oriented problems

---

# 🔗 Connect With Me

<p align="center">

<a href="https://github.com/ujjawal808">
<img src="https://img.shields.io/badge/GitHub-ujjawal808-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://leetcode.com/u/Ujjawalbaliyan/">
<img src="https://img.shields.io/badge/LeetCode-Ujjawalbaliyan-orange?style=for-the-badge&logo=leetcode"/>
</a>

</p>

---

# ⭐ Support

If you find this repository useful, consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**Ujjawal Baliyan**

MCA Student | Java | DSA | Problem Solving | Software Development

> **Keep Learning. Keep Coding. Keep Building. 🚀**
