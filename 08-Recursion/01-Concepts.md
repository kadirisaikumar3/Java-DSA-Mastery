# 📖 Recursion Concepts

---

# What is Recursion?

Recursion is a technique where a function calls itself to solve a smaller version of the same problem.

---

# Basic Structure

```
Function

↓

Base Case

↓

Recursive Call

↓

Smaller Problem

↓

Solution
```

---

# Example

Factorial

```
5!

↓

5 × 4!

↓

4 × 3!

↓

...

↓

1
```

---

# Components

- Base Case
- Recursive Case
- Function Call
- Call Stack

---

# Advantages

- Elegant Solutions
- Less Code
- Natural for Tree & Graph Problems

---

# Disadvantages

- Stack Overflow
- Extra Memory
- Harder to Debug

---

# Complexity

Depends on the recursive relation.

Examples

| Problem | Time |
|----------|------|
| Factorial | O(n) |
| Fibonacci (Naive) | O(2ⁿ) |
| Binary Search | O(log n) |

---

# Interview Tip

Every recursive function must move toward its base case.