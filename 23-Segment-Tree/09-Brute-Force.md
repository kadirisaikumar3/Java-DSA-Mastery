# ❌ Brute Force Approach

---

# Idea

Process every query by traversing the required portion of the array.

---

# Example

Array

```
[2, 5, 1, 4, 3]
```

Query

```
Sum(1,4)
```

Traverse every element between indices 1 and 4.

---

# Complexity

Range Query

```
O(n)
```

Point Update

```
O(1)
```

Multiple Queries

```
O(n × q)
```

---

# Drawbacks

- Slow for large arrays
- Inefficient for repeated queries
- Not suitable for dynamic updates

---

# Better Approach

Use

```
Segment Tree
```

---

# Interview Tip

If there are many range queries, avoid scanning the array repeatedly.