# 🚀 Optimal Approach

---

# What is the Optimal Approach?

Use a single DFS traversal to compute multiple values simultaneously.

---

# Example

Diameter of Binary Tree

Instead of computing height separately,

return height while updating diameter.

---

# Pattern

```
DFS

↓

Compute Left

↓

Compute Right

↓

Combine

↓

Return Result
```

---

# Advantages

- Single Traversal
- No repeated calculations
- Interview preferred

---

# Complexity

Time

```
O(n)
```

Space

```
O(h)
```

where

```
h = Tree Height
```

---

# Interview Tip

Most Tree optimizations use **Postorder DFS** because child information is needed before processing the parent.