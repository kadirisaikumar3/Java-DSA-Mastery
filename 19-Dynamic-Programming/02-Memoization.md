# 📝 Memoization (Top-Down DP)

---

# What is Memoization?

Memoization is a top-down Dynamic Programming technique.

It starts with recursion and stores computed results.

---

# Process

```
Recursion

↓

Compute

↓

Store

↓

Reuse
```

---

# Advantages

- Easy to convert from recursion
- Solves only required states
- Reduces repeated calculations

---

# Example

Fibonacci

Without Memoization

```
fib(5)

↓

fib(4)

↓

fib(3)

↓

Repeated Calls
```

With Memoization

Each Fibonacci value is computed only once.

---

# Complexity

Time

```
O(n)
```

Space

```
O(n)
```

---

# Interview Tip

Memoization = **Recursion + Cache**.