# 🔍 State Space Search

---

# What is State Space Search?

State Space Search explores every possible state of a problem.

Each recursive call moves from one state to another.

---

# Example

Generate Parentheses

```
State

()

↓

(())

↓

(())()
```

---

# General Process

1. Current State
2. Make a Choice
3. Move to Next State
4. Repeat
5. Backtrack

---

# Applications

- Sudoku Solver
- Word Search
- N-Queens
- Maze Problems

---

# Complexity

Depends on the total number of states.

Usually

```
O(2ⁿ)

or

O(n!)
```

---

# Interview Tip

Think of recursion as moving through different states until reaching the final solution.