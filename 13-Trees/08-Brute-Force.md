# ❌ Brute Force Approach

---

# What is Brute Force?

A brute force solution solves Tree problems by performing repeated traversals or recalculating the same information multiple times.

---

# Example

Find the Diameter of a Binary Tree.

Naive Approach

For every node:

- Compute left height
- Compute right height
- Update diameter

This recomputes heights many times.

---

# Complexity

Height Calculation

```
O(n)
```

Performed for every node

```
O(n)
```

Overall

```
O(n²)
```

---

# Drawbacks

- Repeated recursive calls
- Duplicate calculations
- Poor performance on large trees

---

# Interview Tip

Always identify repeated subtree calculations.

Repeated work usually indicates an opportunity for optimization.