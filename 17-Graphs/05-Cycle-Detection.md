# 🔄 Cycle Detection

---

# Undirected Graph

Methods

- DFS + Parent
- BFS + Parent
- Union-Find

---

# Directed Graph

Methods

- DFS + Recursion Stack
- Kahn's Algorithm (Topological Sort)

---

# DFS Logic

```
Visited?

↓

Already Visited

↓

Not Parent?

↓

Cycle Found
```

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

# Applications

- Course Schedule
- Deadlock Detection
- Dependency Checking

---

# Interview Tip

Undirected Graph

↓

Track Parent

Directed Graph

↓

Track Recursion Stack