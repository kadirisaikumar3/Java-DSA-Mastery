# Backtracking Pattern

Backtracking systematically explores all possible solutions while abandoning invalid choices early.

---

## When to Use

- Permutations
- Combinations
- Subsets
- Sudoku Solver
- N-Queens
- Word Search

---

## General Template

```
Choose

↓

Explore

↓

Backtrack

↓

Try Next Choice
```

---

## Common Problems

- Subsets
- Permutations
- Combination Sum
- Letter Combinations
- N Queens
- Palindrome Partitioning

---

## Complexity

Usually exponential.

```
O(2ⁿ)

or

O(n!)
```

depending on the problem.

---

## Key Idea

Undo the current decision before exploring another possibility.

This ensures every valid solution is explored exactly once.