# 📋 Backtracking Cheat Sheet

## Core Pattern

```
Choose

↓

Explore

↓

Undo

↓

Next Choice
```

---

## Complexity

| Problem | Complexity |
|----------|------------|
| Subsets | O(2ⁿ) |
| Permutations | O(n!) |
| N-Queens | O(n!) |
| Sudoku | Exponential |

---

## Common Problems

- Subsets
- Permutations
- Combination Sum
- Generate Parentheses
- Word Search
- N-Queens
- Sudoku Solver

---

## Pattern Recognition

Need all possible solutions?

↓

Think Backtracking

Need constraints?

↓

Use Pruning

---

## Golden Rule

Every recursive call must undo its previous choice before returning.