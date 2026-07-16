# 📋 Bit Manipulation Cheat Sheet

## Common Operations

| Operation | Formula |
|-----------|---------|
| Set ith Bit | `n \| (1 << i)` |
| Clear ith Bit | `n & ~(1 << i)` |
| Toggle ith Bit | `n ^ (1 << i)` |
| Check ith Bit | `(n & (1 << i)) != 0` |

---

## Useful Tricks

Power of Two

```java
(n & (n - 1)) == 0
```

Remove Lowest Set Bit

```java
n = n & (n - 1)
```

Lowest Set Bit

```java
n & (-n)
```

---

## XOR Properties

```text
a ^ a = 0
a ^ 0 = a
a ^ b ^ a = b
```

---

## Pattern Recognition

Unique element?

↓

XOR

Power of Two?

↓

`n & (n-1)`

Generate subsets?

↓

Bit Mask

Count 1 Bits?

↓

Brian Kernighan's Algorithm

---

## Golden Rule

Think in **binary**, not decimal.