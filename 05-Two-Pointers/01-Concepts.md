# 📖 Two Pointer Concepts

---

# What is the Two Pointer Technique?

The Two Pointer technique uses two indices (pointers) to traverse a data structure efficiently.

The pointers move according to specific rules to reduce unnecessary comparisons.

---

# Example

Array

```
[1, 2, 3, 4, 5]
```

Pointers

```
L → 1

          ← R
```

---

# Why Two Pointers?

Instead of checking every pair using nested loops:

```
O(n²)
```

We move pointers intelligently:

```
O(n)
```

---

# Types of Two Pointers

- Opposite Direction
- Same Direction
- Fast & Slow Pointers

---

# Advantages

- Linear Time Complexity
- Less Memory Usage
- Simple Implementation
- Efficient Searching

---

# Disadvantages

- Often requires sorted input
- Not suitable for every problem

---

# Time Complexity

| Technique | Time |
|-----------|------|
| Brute Force | O(n²) |
| Two Pointers | O(n) |

---

# Interview Tip

Whenever a problem asks for:

- Pair Sum
- Palindrome
- Removing Duplicates
- Sorted Array

Think about the Two Pointer approach first.