# ⏱️ Time Complexity

---

# Without Optimization

Find

```
O(n)
```

Union

```
O(n)
```

---

# With Path Compression

Nearly

```
O(α(n))
```

where α(n) is the Inverse Ackermann Function.

---

# Practical Meaning

For all practical input sizes,

```
α(n) ≤ 5
```

So DSU behaves almost like a constant-time data structure.

---

# Summary

| Operation | Complexity |
|-----------|------------|
| Find | O(α(n)) |
| Union | O(α(n)) |
| Space | O(n) |

---

# Interview Tip

Mention **Inverse Ackermann Function** during interviews—it demonstrates a deeper understanding of DSU complexity.