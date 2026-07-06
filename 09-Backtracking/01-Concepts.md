# 📖 Backtracking Concepts

---

# What is Backtracking?

Backtracking is a recursive algorithm that explores all possible choices and removes incorrect choices before continuing.

---

# Core Idea

```
Choose

↓

Explore

↓

Undo (Backtrack)

↓

Try Next Choice
```

---

# Example

Generate all subsets

```
[]

↓

[1]

↓

[1,2]

↓

Backtrack

↓

[1,3]
```

---

# Components

- Choice
- Constraint
- Goal
- Backtracking Step

---

# Advantages

- Finds all valid solutions
- Easy to implement recursively
- Powerful for combinatorial problems

---

# Disadvantages

- Exponential Time Complexity
- Large search space
- Requires pruning for efficiency

---

# Complexity

Most Backtracking problems

```
O(2ⁿ)

or

O(n!)
```

depending on the problem.

---

# Interview Tip

Backtracking =

Choose → Explore → Undo