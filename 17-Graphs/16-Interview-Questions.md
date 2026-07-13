# 🎯 Interview Questions

---

# Beginner

### 1. What is a Graph?

A Graph is a non-linear data structure consisting of vertices (nodes) and edges (connections).

---

### 2. What are the types of Graphs?

- Directed
- Undirected
- Weighted
- Unweighted
- Cyclic
- Acyclic

---

### 3. What is the difference between BFS and DFS?

- BFS explores level by level using a Queue.
- DFS explores depth first using Recursion or a Stack.

---

### 4. What is a Connected Component?

A group of vertices where every vertex is reachable from every other vertex.

---

### 5. What is the complexity of BFS and DFS?

```
O(V + E)
```

---

# Intermediate

### 6. How do you detect cycles?

- Undirected Graph → DFS/BFS with Parent or Union-Find
- Directed Graph → DFS with Recursion Stack or Kahn's Algorithm

---

### 7. What is Topological Sort?

A linear ordering of vertices in a Directed Acyclic Graph (DAG).

---

### 8. Which algorithm finds the shortest path?

- Unweighted Graph → BFS
- Positive Weights → Dijkstra
- Negative Weights → Bellman-Ford

---

### 9. What is Minimum Spanning Tree (MST)?

A subset of edges connecting all vertices with minimum total weight and no cycles.

---

### 10. What is Union-Find?

A data structure that efficiently supports Find and Union operations for disjoint sets.

---

# Google-Level Questions

- Number of Islands
- Clone Graph
- Course Schedule
- Network Delay Time
- Critical Connections
- Word Ladder

---

# Interview Tip

Always identify:

- Graph Type
- Traversal
- Time & Space Complexity