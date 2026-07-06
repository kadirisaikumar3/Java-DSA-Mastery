# ❌ Brute Force Approach

---

# What is Brute Force?

Brute Force explores every possible solution without eliminating invalid paths.

---

# Example

Generate all subsets.

Explore every possible combination regardless of usefulness.

---

# Example Tree

```
[]

├── [1]

│   ├── [1,2]

│   └── [1,3]

└── [2]

    ├── [2,3]

    └── []
```

---

# Complexity

Subsets

```
O(2ⁿ)
```

Permutations

```
O(n!)
```

---

# Drawbacks

- Large search space
- Repeated exploration
- Slow for large inputs

---

# Interview Tip

Explain the brute-force approach before introducing Backtracking with Pruning.