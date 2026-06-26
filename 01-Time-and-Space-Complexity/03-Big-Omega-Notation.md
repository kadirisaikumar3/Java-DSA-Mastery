# 📉 Big-Omega (Ω) Notation

---

# What is Big-Omega?

Big-Omega (Ω) Notation represents the **lower bound** of an algorithm's running time.

It describes the **best-case performance**, i.e., the minimum amount of work an algorithm performs.

Unlike Big-O, which focuses on the maximum running time, Big-Omega focuses on the minimum running time.

---

# Why Big-Omega?

Suppose we perform Linear Search.

Searching for:

```
10
```

Array:

```
10 20 30 40 50
```

The element is found immediately.

Operations:

```
1
```

Best Case Complexity:

```
Ω(1)
```

---

# Example 1

## Linear Search

Best Case

Target found at first index.

```
Ω(1)
```

Worst Case

Target found at last index.

```
O(n)
```

---

# Example 2

Binary Search

Best Case

Middle element is the target.

```
Ω(1)
```

Worst Case

Repeatedly divide the array.

```
O(log n)
```

---

# Why is Big-Omega Important?

It helps us understand the minimum time an algorithm can possibly take.

However, interviewers usually care more about the **worst-case complexity** because it guarantees performance under all inputs.

---

# Interview Tip

If asked:

"What is the best-case complexity?"

Use **Big-Omega (Ω)** notation.

---

# Summary

- Ω represents the lower bound.
- Measures the best-case performance.
- Used less frequently than Big-O in interviews.