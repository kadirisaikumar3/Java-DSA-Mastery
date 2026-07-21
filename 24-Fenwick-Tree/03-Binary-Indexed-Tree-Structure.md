# Binary Indexed Tree Structure

A Fenwick Tree is implemented using a **1-indexed array**.

Example array:

```
Index:

1 2 3 4 5 6 7 8

BIT:

0 2 7 1 15 3 12 5
```

Each position stores the sum of a specific interval.

---

## Node Responsibility

| Index | Stores |
|--------|--------|
|1|1 element|
|2|2 elements|
|3|1 element|
|4|4 elements|
|5|1 element|
|6|2 elements|
|7|1 element|
|8|8 elements|

---

## Parent Relationship

The parent of an index is found using:

```
index + (index & -index)
```

---

## Query Relationship

Move upward using:

```
index - (index & -index)
```

---

## Why Bit Operations?

Bit operations efficiently identify the least significant set bit (LSB), allowing quick traversal through relevant ranges.

This makes both updates and queries logarithmic in complexity.

---

## Visualization

```
               8
          /         \
        4             8
      /   \
     2     4
    / \
   1   2

(Conceptual representation of cumulative ranges)
```

---

Fenwick Trees trade explicit tree nodes for an array-based structure, resulting in lower memory usage and simpler implementation.