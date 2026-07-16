# ⬅️➡️ Left and Right Shift

---

# Left Shift (<<)

Moves all bits to the left by `k` positions.

Formula

```
n << k = n × 2^k
```

Example

```
5 << 1

0101

↓

1010

Result = 10
```

---

# Right Shift (>>)

Moves all bits to the right by `k` positions.

Formula

```
n >> k = n / 2^k
```

(integer division)

Example

```
10 >> 1

1010

↓

0101

Result = 5
```

---

# Complexity

```
O(1)
```

---

# Interview Tip

- Left Shift → Multiply by powers of 2
- Right Shift → Divide by powers of 2