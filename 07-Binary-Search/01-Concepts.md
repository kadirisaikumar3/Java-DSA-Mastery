# 📖 Binary Search Concepts

---

# What is Binary Search?

Binary Search is an efficient searching algorithm that works on sorted data.

It repeatedly divides the search space into two halves.

---

# Visualization

```
Sorted Array

1 3 5 7 9 11 13

        ↑
      Middle
```

---

# Steps

1. Find Middle.
2. Compare with Target.
3. Eliminate one half.
4. Repeat.

---

# Why Binary Search?

Linear Search

```
O(n)
```

Binary Search

```
O(log n)
```

---

# Requirements

- Sorted Data
- Random Access

---

# Advantages

- Extremely Fast
- Logarithmic Time
- Efficient for Large Inputs

---

# Disadvantages

- Requires Sorted Data
- Doesn't work efficiently on Linked Lists

---

# Complexity

| Operation | Time |
|-----------|------|
| Search | O(log n) |

---

# Interview Tip

Whenever the search space is sorted or monotonic,

Think:

**Binary Search**