# 🧠 Recursive Thinking

---

# What is Recursive Thinking?

Instead of solving the entire problem at once, solve a smaller version of the same problem.

---

# Example

Sum of Numbers

Instead of:

```
1 + 2 + 3 + 4 + 5
```

Think:

```
5 +

Sum(4)
```

Then

```
4 +

Sum(3)
```

Until

```
Sum(1)
```

---

# General Formula

```
Problem(n)

↓

Work

+

Problem(n-1)
```

---

# Steps

1. Identify the smaller problem.
2. Define the base case.
3. Trust the recursive call.
4. Combine the result.

---

# Common Recursive Patterns

- Factorial
- Fibonacci
- Binary Search
- Tree Traversal
- DFS
- Backtracking

---

# Interview Tip

Don't try to trace everything at once.

Trust that the recursive call correctly solves the smaller problem.