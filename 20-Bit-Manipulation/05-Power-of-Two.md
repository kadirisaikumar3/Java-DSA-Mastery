# ⚡ Power of Two

---

# Trick

A number is a power of two if:

```java
(n > 0) && ((n & (n - 1)) == 0)
```

---

# Why?

Power of Two

```
8

1000
```

```
7

0111
```

```
1000

&

0111

=

0000
```

---

# Complexity

```
O(1)
```

---

# Applications

- Memory Allocation
- Binary Trees
- Hash Tables
- Competitive Programming

---

# Interview Tip

If you see

```
n & (n-1)
```

Think:

- Power of Two
- Remove Lowest Set Bit