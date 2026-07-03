# 📖 Sliding Window Concepts

---

# What is Sliding Window?

Sliding Window is a technique used to process contiguous elements efficiently by maintaining a window over the data.

Instead of recomputing values for every possible subarray, the window slides across the array.

---

# Visualization

```
Array

1 2 3 4 5 6 7

Window Size = 3

[1 2 3]

   ↓

[2 3 4]

   ↓

[3 4 5]
```

---

# Why Sliding Window?

Brute Force

```
O(n²)
```

Sliding Window

```
O(n)
```

---

# Types

- Fixed Size Window
- Variable Size Window

---

# Advantages

- Linear Time
- Efficient Memory Usage
- Simple Implementation
- Excellent for Continuous Segments

---

# Disadvantages

- Works only on contiguous elements
- Pattern recognition required

---

# Time Complexity

| Technique | Time |
|-----------|------|
| Brute Force | O(n²) |
| Sliding Window | O(n) |

---

# Interview Tip

Whenever you see:

- Subarray
- Substring
- Continuous Elements

Think:

Sliding Window