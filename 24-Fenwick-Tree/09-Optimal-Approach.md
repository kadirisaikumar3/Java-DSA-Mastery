# Optimal Approach

Fenwick Tree improves efficiency by storing partial prefix sums.

Instead of recalculating sums every time, cumulative information is maintained dynamically.

---

## Idea

Store cumulative values in a Binary Indexed Tree.

Each node represents the sum of a specific interval.

---

## Query

```
while(index > 0)
{
    sum += BIT[index];
    index -= index & (-index);
}
```

---

## Update

```
while(index <= n)
{
    BIT[index] += value;
    index += index & (-index);
}
```

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Prefix Sum | O(log n) |
| Update | O(log n) |
| Space | O(n) |

---

## Advantages

- Fast Queries
- Fast Updates
- Simple Implementation
- Low Memory Usage
- Excellent for Competitive Programming

Fenwick Tree is the preferred choice when only prefix/range sum queries and point updates are required.