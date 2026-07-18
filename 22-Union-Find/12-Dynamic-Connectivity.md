# 🔗 Dynamic Connectivity

---

# What is Dynamic Connectivity?

Determine whether two nodes are connected while edges are added dynamically.

---

# Operations

- Union
- Find
- Connectivity Query

---

# Example

```
union(1,2)

union(2,3)

find(1) == find(3)

↓

True
```

---

# Applications

- Network Design
- Social Networks
- Distributed Systems
- Online Graph Processing

---

# Complexity

```
Almost O(1)
```

per operation.

---

# Interview Tip

Whenever the graph changes dynamically,

↓

Think **Union Find**.