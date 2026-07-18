# 🔗 Disjoint Set Union (DSU)

---

# What is DSU?

A Disjoint Set Union data structure keeps track of multiple non-overlapping sets.

Each set has a representative called the **parent**.

---

# Parent Array

Example

```
Index

0 1 2 3 4
```

Parent

```
0 1 2 3 4
```

Initially,

Every node is its own parent.

---

# Goal

Efficiently:

- Merge Sets
- Find Set Representative

---

# Operations

- Find(x)
- Union(x, y)

---

# Advantages

- Efficient Connectivity
- Fast Merging
- Low Memory Usage

---

# Interview Tip

The parent array is the backbone of every DSU implementation.