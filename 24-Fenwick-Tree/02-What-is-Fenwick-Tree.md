# What is a Fenwick Tree?

A **Fenwick Tree**, or **Binary Indexed Tree (BIT)**, is a data structure designed to efficiently maintain cumulative values while supporting updates.

Unlike a Segment Tree, it uses a single array and clever bit manipulation.

---

## Main Operations

### Prefix Sum

Find the sum of elements from index `1` to `i`.

Example:

```
Sum(5)
=
a1 + a2 + a3 + a4 + a5
```

---

### Point Update

Increase or decrease a value at a specific index.

Example:

```
Update(4, +3)
```

Adds `3` to the value at index `4` and updates all affected cumulative sums.

---

## Why "Binary Indexed"?

Each index stores information about a range determined by its binary representation.

The least significant set bit (LSB) determines the size of the range.

Example:

```
Index 12

Binary:
1100

LSB = 0100

Range Size = 4
```

---

## Advantages

- Simple implementation
- Fast updates
- Fast prefix sums
- Low memory consumption
- Excellent for competitive programming

---

Fenwick Trees are commonly preferred when only prefix/range sum queries and point updates are required.