# Top K Elements

The **Top K Elements Pattern** is commonly solved using a **Heap (Priority Queue)**.

It efficiently keeps track of the largest or smallest K elements.

---

## When to Use

Use this pattern for:

- K Largest Elements
- K Smallest Elements
- Top Frequent Elements
- K Closest Points
- Merge K Sorted Lists

---

## Example

Array:

```
7 2 9 4 1 8 6
```

K = 3

Result:

```
9 8 7
```

---

## Common Data Structures

- Min Heap
- Max Heap
- Priority Queue

---

## Common Problems

- Top K Frequent Elements
- K Closest Points to Origin
- Kth Largest Element
- Merge K Sorted Lists
- K Closest Numbers

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Time | O(n log k) |
| Space | O(k) |

---

## Key Idea

Maintain only the best **K** elements using a heap instead of sorting the entire dataset.