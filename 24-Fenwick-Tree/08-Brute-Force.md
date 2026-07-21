# Brute Force Approach

Before learning Fenwick Trees, let's examine the traditional method.

---

## Problem

Support two operations:

- Prefix Sum Query
- Point Update

---

## Prefix Sum

For every query:

```
sum = 0

for(i = 1; i <= index; i++)
    sum += arr[i];
```

---

## Update

```
arr[index] += value;
```

---

## Example

Array:

```
2 4 1 7 3
```

Query:

```
PrefixSum(5)

2 + 4 + 1 + 7 + 3 = 17
```

Update:

```
Index = 4

Add = 5
```

Updated Array:

```
2 4 1 12 3
```

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Prefix Sum | O(n) |
| Update | O(1) |

---

## Drawback

For a large number of queries, repeatedly traversing the array becomes inefficient.

Fenwick Tree reduces query time to **O(log n)**.