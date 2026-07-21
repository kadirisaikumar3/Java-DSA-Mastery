# Prefix Sum Query

One of the primary operations of a Fenwick Tree is calculating the **Prefix Sum**.

A Prefix Sum Query returns the sum of all elements from index **1** to a given index **i**.

---

## Example

Array:

```
Index:  1 2 3 4 5
Value:  2 4 1 7 3
```

Find:

```
PrefixSum(4)

= 2 + 4 + 1 + 7
= 14
```

---

## Algorithm

```
sum = 0

while(index > 0)
{
    sum += BIT[index];
    index -= index & (-index);
}

return sum;
```

---

## Traversal Example

Suppose:

```
Index = 13

Binary:
1101
```

Traversal:

```
13
↓

12

↓

8

↓

0
```

Each visited node contributes to the answer.

---

## Time Complexity

| Operation | Complexity |
|-----------|------------|
| Prefix Sum | O(log n) |

---

Fenwick Tree answers Prefix Sum Queries efficiently by visiting only a logarithmic number of nodes.