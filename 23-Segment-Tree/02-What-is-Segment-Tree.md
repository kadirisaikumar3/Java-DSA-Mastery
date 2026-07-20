# 🌲 What is Segment Tree?

---

# Definition

A Segment Tree divides an array into smaller segments.

Each internal node stores information about a specific range.

---

# Example

Array

```
[2, 5, 1, 4]
```

Segment Tree

```
          12
        /    \
       7      5
     /  \    / \
    2   5   1   4
```

Each parent stores the sum of its children.

---

# Features

- Binary Tree
- Height = O(log n)
- Supports Fast Queries
- Supports Updates

---

# Memory Requirement

Typically

```
4 × n
```

array size is allocated for implementation.

---

# Interview Tip

A Segment Tree is **not** a Binary Search Tree.

It is built on array intervals, not key ordering.