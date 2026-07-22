# Sliding Window Pattern

The Sliding Window Pattern is used to process contiguous subarrays or substrings efficiently.

Instead of recalculating each window, we expand and shrink a window dynamically.

---

## When to Use

Apply this pattern for:

- Subarrays
- Substrings
- Maximum/Minimum window
- Longest sequence
- Fixed-size windows
- Variable-size windows

---

## Example

Find the maximum sum subarray of size 3.

```
Array:

2 4 1 7 3 8
```

Window:

```
[2 4 1]

↓

[4 1 7]

↓

[1 7 3]

↓

[7 3 8]
```

Each move updates the sum by removing one element and adding another.

---

## Common Problems

- Maximum Sum Subarray
- Longest Substring Without Repeating Characters
- Minimum Window Substring
- Permutation in String
- Fruits Into Baskets

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Time | O(n) |
| Space | O(1) or O(k) |

---

## Key Idea

Maintain a moving window and update results incrementally instead of recomputing from scratch.