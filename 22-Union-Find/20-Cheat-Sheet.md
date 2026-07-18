# 📋 Union Find Cheat Sheet

## Core Operations

Find

```java
find(x)
```

Union

```java
union(x, y)
```

---

## Optimizations

- Path Compression
- Union by Rank
- Union by Size

---

## Time Complexity

| Operation | Complexity |
|-----------|------------|
| Find | O(α(n)) |
| Union | O(α(n)) |
| Space | O(n) |

---

## Common Applications

- Connected Components
- Cycle Detection
- Kruskal's Algorithm
- Dynamic Connectivity
- Network Connectivity

---

## Pattern Recognition

Connectivity?

↓

DSU

Cycle Detection?

↓

Union Find

Minimum Spanning Tree?

↓

Kruskal + DSU

Dynamic Graph?

↓

Union Find

---

## Golden Rule

Always combine **Path Compression** with **Union by Rank** (or **Union by Size**) for optimal performance.