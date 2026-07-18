# 🌐 Connected Components

---

# Problem

Find the number of connected components in a graph.

---

# Approach

Initially

Every node is its own component.

For every edge:

```
Union(u, v)
```

Finally,

Count unique parents.

---

# Complexity

```
O(E × α(n))
```

---

# Applications

- Social Networks
- Computer Networks
- Image Segmentation
- Clustering

---

# Interview Tip

DSU is faster than repeatedly running DFS/BFS when processing many union operations.