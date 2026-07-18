# ❌ Brute Force Approach

---

# Idea

Use DFS or BFS after every edge insertion.

---

# Complexity

```
O(V + E)
```

per query.

---

# Drawbacks

- Slow
- Repeated Traversals
- Poor Scalability

---

# Better Approach

Use

```
Union Find
```

---

# Interview Tip

If multiple connectivity queries exist,

↓

Avoid repeated DFS/BFS.