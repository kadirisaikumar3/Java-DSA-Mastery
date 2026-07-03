# ⚡ Better Approach

---

# What is a Better Approach?

Instead of recalculating every window, reuse previously computed information.

---

# Example

Maximum Sum Subarray

Instead of summing every element again:

Remove the outgoing element.

Add the incoming element.

---

# Example

```
Window

[2 4 1]

↓

Remove 2

↓

Add 5

↓

[4 1 5]
```

---

# Complexity

Time

```
O(n)
```

Space

```
O(1)
```

---

# Benefits

- No repeated calculations
- Faster execution
- Less CPU usage

---

# Interview Tip

Whenever the window shifts by one position, reuse previous calculations.