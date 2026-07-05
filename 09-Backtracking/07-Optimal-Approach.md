# 🚀 Optimal Approach

---

# What is the Optimal Approach?

Optimize recursion by eliminating repeated computations.

Common techniques include:

- Memoization
- Dynamic Programming
- Iteration (when applicable)

---

# Example

Memoized Fibonacci

```java
int fibonacci(int n){

    if(n <= 1)

        return n;

    if(dp[n] != -1)

        return dp[n];

    return dp[n] = fibonacci(n-1) + fibonacci(n-2);

}
```

---

# Complexity

| Technique | Time | Space |
|-----------|------|-------|
| Naive Recursion | O(2ⁿ) | O(n) |
| Memoization | O(n) | O(n) |

---

# Advantages

- Eliminates repeated work
- Faster execution
- Suitable for large inputs

---

# Interview Tip

First explain the recursive solution, then optimize it using Memoization or Dynamic Programming if overlapping subproblems exist.