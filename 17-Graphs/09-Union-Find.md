# 🔗 Union-Find (Disjoint Set Union)

---

# What is DSU?

Union-Find maintains disjoint sets efficiently.

Supports:

- Find
- Union

---

# Optimizations

- Path Compression
- Union by Rank
- Union by Size

---

# Applications

- Cycle Detection
- Kruskal's Algorithm
- Connected Components

---

# Complexity

Nearly

```
O(1)
```

Amortized

---

# Java Template

```java
int find(int x){

    if(parent[x] != x)

        parent[x] = find(parent[x]);

    return parent[x];

}
```

---

# Interview Tip

DSU is one of the fastest methods for connectivity problems.    