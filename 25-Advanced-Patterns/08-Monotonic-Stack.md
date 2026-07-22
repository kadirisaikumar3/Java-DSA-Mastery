# Monotonic Stack

A **Monotonic Stack** is a stack that maintains its elements in either increasing or decreasing order.

It is extremely useful for solving "Next Greater", "Previous Smaller", and similar problems in linear time.

---

## When to Use

Use this pattern for:

- Next Greater Element
- Previous Greater Element
- Previous Smaller Element
- Largest Rectangle in Histogram
- Daily Temperatures
- Stock Span Problem

---

## Example

Array:

```
2 1 5 6 2 3
```

Monotonic Increasing Stack:

```
Push

↓

Maintain Increasing Order

↓

Pop Until Valid

↓

Push Current
```

---

## Common Problems

- Next Greater Element I & II
- Daily Temperatures
- Largest Rectangle in Histogram
- Trapping Rain Water
- Stock Span

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Time | O(n) |
| Space | O(n) |

---

## Key Idea

Each element is pushed and popped at most once, giving an overall linear-time solution.