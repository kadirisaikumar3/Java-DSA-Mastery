# ❌ Brute Force Approach

---

# What is Brute Force?

Solve the problem using pure recursion by exploring every possible choice.

---

# Example

Coin Change

For every coin,

Try:

- Take the coin
- Skip the coin

This generates many repeated subproblems.

---

# Complexity

Usually

```
Exponential
```

Examples

```
O(2ⁿ)

O(n!)
```

---

# Drawbacks

- Repeated calculations
- Slow execution
- High recursion depth

---

# Interview Tip

Whenever recursion revisits the same state,

↓

Think **Dynamic Programming**.