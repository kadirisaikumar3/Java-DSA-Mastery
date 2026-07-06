# ✂️ Pruning

---

# What is Pruning?

Pruning is the process of stopping the exploration of a branch when it cannot produce a valid solution.

Instead of exploring every possibility, we eliminate impossible paths early.

---

# Why Pruning?

Without Pruning

```
Explore Every Branch
```

With Pruning

```
Skip Invalid Branches
```

This greatly improves efficiency.

---

# Example

Combination Sum

Target = 7

```
Current Sum = 8

↓

Stop Exploring

↓

Backtrack
```

No need to continue because the target has already been exceeded.

---

# Common Pruning Techniques

- Current Sum > Target
- Duplicate Elements
- Invalid Position
- Constraint Violation

---

# Applications

- N-Queens
- Sudoku Solver
- Combination Sum
- Word Search
- Palindrome Partitioning

---

# Complexity

Pruning reduces the search space significantly but the worst-case complexity often remains:

```
O(2ⁿ)

or

O(n!)
```

---

# Interview Tip

Always look for conditions where further exploration is unnecessary.