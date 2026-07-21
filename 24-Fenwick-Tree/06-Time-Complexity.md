# Time Complexity

Fenwick Trees provide efficient performance for dynamic prefix sum operations.

---

## Complexity Table

| Operation | Time Complexity |
|-----------|-----------------|
| Build Tree | O(n log n) |
| Prefix Sum Query | O(log n) |
| Point Update | O(log n) |
| Space | O(n) |

---

## Comparison

| Data Structure | Query | Update |
|---------------|-------|--------|
| Array | O(n) | O(1) |
| Prefix Sum Array | O(1) | O(n) |
| Fenwick Tree | O(log n) | O(log n) |
| Segment Tree | O(log n) | O(log n) |

---

## Why O(log n)?

Each operation moves by removing or adding the **Least Significant Set Bit (LSB)**.

This skips large portions of the array, reducing the number of visited indices.

---

## Memory Usage

Fenwick Tree requires:

```
n + 1
```

elements because it is implemented as a **1-indexed array**.

---

Fenwick Trees strike an excellent balance between speed, simplicity, and memory efficiency.