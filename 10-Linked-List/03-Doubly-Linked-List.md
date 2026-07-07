# ⬅️➡️ Doubly Linked List

---

# What is a Doubly Linked List?

Each node stores:

- Previous Pointer
- Data
- Next Pointer

---

# Visualization

```
NULL ← 10 ⇄ 20 ⇄ 30 → NULL
```

---

# Node Structure

```java
class Node{

    Node prev;

    int data;

    Node next;

}
```

---

# Advantages

- Forward Traversal
- Backward Traversal
- Easier Deletion

---

# Disadvantages

- Extra Memory
- More Pointer Updates

---

# Applications

- Browser History
- Undo/Redo
- LRU Cache

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(1) |
| Delete | O(1) |

---

# Interview Tip

Many system design problems like **LRU Cache** use Doubly Linked Lists.