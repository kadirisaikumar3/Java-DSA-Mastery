# Cheat Sheet

## Operations

| Operation | Complexity |
|-----------|------------|
| Build | O(n log n) |
| Prefix Sum | O(log n) |
| Point Update | O(log n) |
| Space | O(n) |

---

## Query Formula

```
while(index > 0)
{
    sum += BIT[index];
    index -= index & (-index);
}
```

---

## Update Formula

```
while(index <= n)
{
    BIT[index] += value;
    index += index & (-index);
}
```

---

## LSB Formula

```
index & (-index)
```

---

## Range Query

```
Query(R)

-

Query(L-1)
```

---

## Advantages

✔ Fast Queries

✔ Fast Updates

✔ Easy Implementation

✔ Low Memory

✔ Excellent for Competitive Programming

---

## Limitations

- Supports Prefix-based Operations
- Less Flexible than Segment Tree