# 📊 Big-Theta (Θ) Notation

---

# What is Big-Theta?

Big-Theta (Θ) Notation represents the **tight bound** of an algorithm.

It describes the running time when the **best case and worst case grow at the same rate**.

---

# Why Big-Theta?

Suppose an algorithm always traverses the entire array.

Example:

Finding the sum of all elements.

```
1 2 3 4 5
```

Regardless of the input values, every element must be visited.

Best Case

```
Θ(n)
```

Worst Case

```
Θ(n)
```

Average Case

```
Θ(n)
```

---

# Example

Array Traversal

```
for(int i = 0; i < n; i++)
```

Every element is visited once.

Complexity

```
Θ(n)
```

---

# Difference

Big-O

Upper Bound

Big-Omega

Lower Bound

Big-Theta

Exact Growth Rate

---

# Real-world Example

Finding Maximum Element

No matter where the maximum exists, every element must be checked.

Complexity

```
Θ(n)
```

---

# Interview Tip

Use Θ notation when the algorithm consistently performs the same amount of work regardless of input arrangement.

---

# Summary

- Θ represents the tight bound.
- Best Case = Worst Case.
- Indicates exact asymptotic growth.