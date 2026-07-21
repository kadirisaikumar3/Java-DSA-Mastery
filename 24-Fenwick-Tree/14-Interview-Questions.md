# Interview Questions

## Beginner Level

### 1. What is a Fenwick Tree?

A Fenwick Tree (Binary Indexed Tree) is a data structure that efficiently supports:

- Prefix Sum Queries
- Point Updates

Both operations take **O(log n)** time.

---

### 2. Why is it called a Binary Indexed Tree?

Because each index stores cumulative information determined by its binary representation.

---

### 3. What operations are supported?

- Prefix Sum Query
- Point Update
- Range Sum Query (using two prefix sums)

---

### 4. Why is Fenwick Tree 1-indexed?

The Least Significant Set Bit (LSB) logic works naturally with 1-based indexing.

---

### 5. Difference between Prefix Sum Array and Fenwick Tree?

| Prefix Sum | Fenwick Tree |
|------------|--------------|
| Query: O(1) | O(log n) |
| Update: O(n) | O(log n) |

---

## Intermediate Level

### 6. Explain `index & (-index)`.

It extracts the Least Significant Set Bit (LSB), which determines the size of the range represented by a node.

---

### 7. Why is update O(log n)?

Because each update visits only logarithmically many indices.

---

### 8. Can Fenwick Tree answer range sum queries?

Yes.

```
Range(L,R)

=

Prefix(R) - Prefix(L-1)
```

---

### 9. Space Complexity?

```
O(n)
```

---

### 10. When should Segment Tree be preferred?

When:

- Range Updates
- Minimum Queries
- Maximum Queries
- GCD Queries
- Complex interval operations

are required.

---

## Google Style Questions

- Count Inversions
- Count Smaller Numbers After Self
- Dynamic Prefix Sum
- Frequency Counting
- Offline Query Processing