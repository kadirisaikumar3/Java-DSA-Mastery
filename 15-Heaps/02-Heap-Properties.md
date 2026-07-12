# 📏 Heap Properties

---

# Min Heap

Every parent node is smaller than or equal to its children.

```
        5
      /   \
     8     10
    / \   /
   15 20 12
```

Smallest element is always at the root.

---

# Max Heap

Every parent node is greater than or equal to its children.

```
        20
      /    \
     15     10
    / \    /
   8  5   7
```

Largest element is always at the root.

---

# Complete Binary Tree Property

Nodes are filled level by level from left to right.

---

# Array Representation

For index `i`

```
Left Child  = 2*i + 1

Right Child = 2*i + 2

Parent      = (i - 1)/2
```

---

# Interview Tip

The Heap Property applies only between a node and its children.

It does **not** guarantee sorted order.