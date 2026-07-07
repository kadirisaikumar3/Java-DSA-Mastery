# 🔄 Circular Linked List

---

# What is a Circular Linked List?

A Circular Linked List is a linked list where the last node points back to the first node instead of NULL.

---

# Visualization

```
        ┌────────────────────┐
        │                    │
        ▼                    │
10 → 20 → 30 → 40 ───────────┘
```

---

# Types

- Singly Circular Linked List
- Doubly Circular Linked List

---

# Advantages

- Continuous Traversal
- Efficient Circular Operations
- No NULL at the End

---

# Disadvantages

- More Complex Implementation
- Infinite Loop Risk
- Harder Debugging

---

# Applications

- Round Robin Scheduling
- Music Playlists
- Multiplayer Games
- Circular Buffers

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(1) |
| Delete | O(1) |
| Traverse | O(n) |

---

# Interview Tip

Always stop traversal when you reach the starting node again.