# Fast and Slow Pointers

The **Fast and Slow Pointers Pattern** uses two pointers moving at different speeds to solve problems involving linked lists and cycles.

This pattern is also known as **Floyd's Cycle Detection Algorithm**.

---

## When to Use

Use this pattern for:

- Detecting cycles
- Finding the middle node
- Finding the start of a cycle
- Happy Number
- Circular Arrays

---

## Example

Linked List:

```
1 → 2 → 3 → 4 → 5
          ↑     ↓
          ← ← ←
```

Pointers:

```
Slow → moves 1 step

Fast → moves 2 steps
```

If both pointers meet, a cycle exists.

---

## Common Problems

- Linked List Cycle
- Linked List Cycle II
- Middle of Linked List
- Happy Number
- Circular Array Loop

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Time | O(n) |
| Space | O(1) |

---

## Key Idea

Move one pointer twice as fast as the other. If they meet, a cycle is present; otherwise, the list ends without a cycle.