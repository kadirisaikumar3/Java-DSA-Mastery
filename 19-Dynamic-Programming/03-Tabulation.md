# 📊 Tabulation (Bottom-Up DP)

---

# What is Tabulation?

Tabulation is a bottom-up Dynamic Programming technique.

It starts from the smallest subproblem and builds toward the final answer.

---

# Process

```
Base Cases

↓

Fill DP Table

↓

Final Answer
```

---

# Advantages

- No recursion
- No stack overflow
- Usually faster than Memoization

---

# Example

Fibonacci

```
dp[0] = 0

dp[1] = 1

dp[i] = dp[i-1] + dp[i-2]
```

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

Can often be optimized to

```
O(1)
```

---

# Memoization vs Tabulation

| Memoization | Tabulation |
|-------------|------------|
| Top-Down | Bottom-Up |
| Uses Recursion | Uses Loops |
| Cache | DP Table |

---

# Interview Tip

If recursion causes stack overflow,

↓

Convert to **Tabulation**.