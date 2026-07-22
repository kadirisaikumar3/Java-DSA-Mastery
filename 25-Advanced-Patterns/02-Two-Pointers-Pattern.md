# Two Pointers Pattern

The Two Pointers Pattern uses two indices that move through an array or string to solve problems efficiently.

Instead of nested loops, both pointers traverse the data together.

---

## When to Use

Use this pattern when dealing with:

- Sorted arrays
- Pair problems
- Palindromes
- Removing duplicates
- Partitioning arrays

---

## Example

Find two numbers whose sum equals a target.

```
Array:

1 2 4 6 8 10

Target = 12
```

Pointers:

```
L                 R

1 2 4 6 8 10
```

Move pointers based on comparison until the target is found.

---

## Common Problems

- Two Sum II
- Container With Most Water
- Valid Palindrome
- Remove Duplicates
- 3Sum
- Trapping Rain Water

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Time | O(n) |
| Space | O(1) |

---

## Key Idea

Instead of checking every pair, intelligently move one pointer at a time based on the current result.