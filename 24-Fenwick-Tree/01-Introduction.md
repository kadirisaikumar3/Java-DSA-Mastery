# Introduction

Suppose you have an array:

```
[2, 5, 1, 7, 3, 9]
```

You need to repeatedly answer questions like:

- Sum from index 0 to 4
- Sum from index 2 to 5
- Update index 3 by adding 6
- Again calculate sums

A normal array performs updates quickly but prefix sums slowly.

A Prefix Sum Array answers queries quickly but updates slowly.

Fenwick Tree provides the best balance by supporting both operations efficiently.

---

## Why Fenwick Tree?

Instead of recalculating sums after every update, Fenwick Tree stores partial sums.

This allows:

- Fast Updates
- Fast Queries
- Low Memory Usage

---

## Key Idea

Store cumulative information in powers of two.

Each node stores the sum of a specific range.

Bit manipulation determines which range each node represents.

---

## Complexity

| Operation | Time |
|-----------|------|
| Build | O(n log n) |
| Prefix Sum | O(log n) |
| Update | O(log n) |
| Space | O(n) |

---

Fenwick Tree is one of the most elegant data structures combining arrays and bit manipulation.