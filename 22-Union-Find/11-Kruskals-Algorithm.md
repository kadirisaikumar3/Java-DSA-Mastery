# 🌳 Kruskal's Algorithm

---

# Purpose

Find the Minimum Spanning Tree (MST).

---

# Algorithm

1. Sort all edges by weight.
2. Process edges in increasing order.
3. If edge forms no cycle:

```
Include Edge
```

Otherwise

```
Skip Edge
```

---

# Why DSU?

DSU quickly determines whether adding an edge creates a cycle.

---

# Complexity

Sorting

```
O(E log E)
```

Union Find

```
O(E × α(n))
```

Overall

```
O(E log E)
```

---

# Interview Tip

Kruskal's Algorithm always uses **Union Find** for efficient cycle detection.