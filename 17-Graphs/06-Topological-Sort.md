# 📑 Topological Sort

---

# What is Topological Sort?

A linear ordering of vertices such that

For every directed edge

```
u → v
```

u appears before v.

---

# Conditions

- Directed Graph
- Acyclic Graph (DAG)

---

# Methods

- DFS
- Kahn's Algorithm (BFS)

---

# Applications

- Course Schedule
- Build Systems
- Dependency Resolution

---

# Complexity

Time

```
O(V + E)
```

Space

```
O(V)
```

---

# Interview Tip

If the graph contains a cycle,

Topological Sort is **not possible**.