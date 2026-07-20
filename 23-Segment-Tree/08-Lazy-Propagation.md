# ⚡ Lazy Propagation

---

# What is Lazy Propagation?

Lazy Propagation is an optimization used for efficient range updates.

Instead of updating every element immediately,

updates are postponed until necessary.

---

# Why Use It?

Without Lazy Propagation

Range Update

```
O(n)
```

With Lazy Propagation

Range Update

```
O(log n)
```

---

# Extra Array

```java
int[] lazy = new int[4 * n];
```

Stores pending updates.

---

# Advantages

- Fast Range Updates
- Efficient Queries
- Avoids Repeated Work

---

# Applications

- Range Addition
- Range Assignment
- Competitive Programming
- Dynamic Interval Problems

---

# Interview Tip

Lazy Propagation is useful only when there are **frequent range updates**.