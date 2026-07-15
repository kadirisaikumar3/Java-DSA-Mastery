# 🧩 Dynamic Programming Concepts

---

# What is Dynamic Programming?

Dynamic Programming is an optimization technique that stores previously computed results to avoid solving the same subproblem multiple times.

---

# Two Key Properties

- Overlapping Subproblems
- Optimal Substructure

---

# Overlapping Subproblems

The same subproblem appears multiple times.

Instead of recomputing it,

Store the answer.

---

# Optimal Substructure

The optimal solution can be built using optimal solutions of smaller subproblems.

---

# Advantages

- Faster than brute force
- Avoids repeated work
- Efficient for optimization problems

---

# Disadvantages

- Higher memory usage
- State definition can be difficult

---

# Complexity

Usually

```
O(n)

O(n²)

O(n × m)
```

Depends on the state transition.

---

# Interview Tip

Whenever recursion repeatedly solves the same subproblem,

↓

Think **Dynamic Programming**.