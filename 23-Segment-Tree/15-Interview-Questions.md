# 🎯 Interview Questions

---

# Beginner

### 1. What is a Segment Tree?

A Segment Tree is a binary tree used for efficient range queries and updates on an array.

---

### 2. Why use a Segment Tree?

To answer range queries and perform updates efficiently in logarithmic time.

---

### 3. What are the main operations?

- Build
- Query
- Update

---

### 4. What is the height of a Segment Tree?

```
O(log n)
```

---

### 5. Why is 4 × n memory allocated?

It safely stores all tree nodes regardless of the array size.

---

# Intermediate

### 6. What is Lazy Propagation?

An optimization technique that delays range updates until they are actually needed.

---

### 7. Difference between Segment Tree and Prefix Sum?

| Prefix Sum | Segment Tree |
|------------|--------------|
| Static Arrays | Dynamic Arrays |
| O(1) Query | O(log n) Query |
| O(n) Update | O(log n) Update |

---

### 8. Why is Build O(n)?

Each array element contributes to the construction of the tree exactly once.

---

### 9. What are the three overlap cases?

- No Overlap
- Partial Overlap
- Complete Overlap

---

### 10. Where are Segment Trees used?

- Range Queries
- Competitive Programming
- Financial Analytics
- Databases
- Dynamic Interval Problems

---

# Google-Level Questions

- Range Sum Query
- Range Minimum Query
- Falling Squares
- Range Module
- My Calendar III
- Skyline Problem
- Count of Smaller Numbers After Self

---

# Interview Tip

Always explain:

- Tree Structure
- Node Range
- Overlap Cases
- Time & Space Complexity