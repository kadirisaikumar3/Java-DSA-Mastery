# ⏱️ Time Complexity

---

# Segment Tree Operations

| Operation | Complexity |
|-----------|------------|
| Build | O(n) |
| Range Query | O(log n) |
| Point Update | O(log n) |
| Space | O(4n) |

---

# Why O(log n)?

Each query or update visits only a limited number of nodes along the tree height.

Tree Height

```
O(log n)
```

---

# Comparison

| Operation | Brute Force | Segment Tree |
|-----------|------------|--------------|
| Range Query | O(n) | O(log n) |
| Update | O(1) | O(log n) |

---

# Interview Tip

Always mention both **Build = O(n)** and **Query/Update = O(log n)** during interviews.