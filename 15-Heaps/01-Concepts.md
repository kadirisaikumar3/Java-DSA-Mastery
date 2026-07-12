# 🏔️ Heap Concepts

---

# What is a Heap?

A Heap is a Complete Binary Tree that satisfies the Heap Property.

---

# Complete Binary Tree

A Complete Binary Tree is filled level by level.

Only the last level may be incomplete, and nodes are filled from left to right.

Example

```
        10
      /    \
     20     30
    / \    /
   40 50  60
```

---

# Heap Property

Two types

- Min Heap
- Max Heap

---

# Characteristics

- Complete Binary Tree
- Efficient Insert/Delete
- Root contains Highest or Lowest Priority

---

# Advantages

- Fast Priority Operations
- Efficient Top-K Queries
- Supports Priority Queue

---

# Disadvantages

- Searching arbitrary elements is slow
- Not suitable for ordered traversal

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(log n) |
| Delete | O(log n) |
| Peek | O(1) |

---

# Interview Tip

Remember:

A Heap is **not** a Binary Search Tree.

It only satisfies the Heap Property.