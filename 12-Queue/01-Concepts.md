# 📖 Queue Concepts

---

# What is a Queue?

A Queue is a linear data structure that follows the **First In, First Out (FIFO)** principle.

The first element inserted is the first one removed.

---

# Visualization

```
Front                        Rear

↓

10 → 20 → 30 → 40

↑

Remove Here          Insert Here
```

---

# FIFO Principle

```
Enqueue 10

Enqueue 20

Enqueue 30

↓

Dequeue

10

↓

Dequeue

20
```

---

# Basic Operations

- Enqueue
- Dequeue
- Front (Peek)
- Rear
- isEmpty()
- Size()

---

# Advantages

- Efficient insertion
- Efficient deletion
- FIFO processing
- Simple implementation

---

# Disadvantages

- No random access
- Front-only deletion

---

# Complexity

| Operation | Time |
|-----------|------|
| Enqueue | O(1) |
| Dequeue | O(1) |
| Front | O(1) |

---

# Interview Tip

Whenever elements must be processed in arrival order,

Think:

**Queue**