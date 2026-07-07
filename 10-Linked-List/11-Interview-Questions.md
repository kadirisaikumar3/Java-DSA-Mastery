# 🎯 Interview Questions

---

# Beginner

### 1. What is a Linked List?

A Linked List is a linear data structure where elements are stored as nodes connected using pointers.

---

### 2. What are the types of Linked Lists?

- Singly Linked List
- Doubly Linked List
- Circular Linked List
- Circular Doubly Linked List

---

### 3. Why are insertions faster in a Linked List?

Because pointers can be updated without shifting elements.

---

### 4. What is the time complexity of searching?

```
O(n)
```

---

### 5. What is a Node?

A node contains:

- Data
- Pointer(s) to other nodes

---

# Intermediate

### 6. What is the Fast & Slow Pointer technique?

A two-pointer approach where one pointer moves twice as fast as the other.

Applications:

- Find Middle Node
- Detect Cycle
- Find Start of Cycle

---

### 7. What is Floyd's Cycle Detection Algorithm?

A cycle detection algorithm using fast and slow pointers.

---

### 8. Why use a Dummy Node?

A dummy node simplifies insertion and deletion at the head of the list.

---

### 9. How do you reverse a Linked List?

By updating each node's `next` pointer iteratively or recursively.

---

### 10. What is the difference between Arrays and Linked Lists?

| Array | Linked List |
|--------|-------------|
| Contiguous Memory | Dynamic Memory |
| O(1) Access | O(n) Access |
| Costly Insert/Delete | Efficient Insert/Delete |

---

# Google-Level Questions

- Reverse Nodes in K Group
- Merge K Sorted Lists
- Copy List with Random Pointer
- Add Two Numbers
- Linked List Cycle II
- LRU Cache

---

# Interview Tip

Always explain pointer movement using a diagram before writing code.