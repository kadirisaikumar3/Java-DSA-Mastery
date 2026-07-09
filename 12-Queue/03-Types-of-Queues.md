# 🔄 Types of Queues

---

# 1. Simple Queue

Follows FIFO.

```
10 → 20 → 30
```

---

# 2. Circular Queue

The last position connects back to the first.

Applications

- CPU Scheduling
- Circular Buffer

---

# 3. Deque

Double Ended Queue.

Supports insertion and deletion from both ends.

Applications

- Sliding Window
- Monotonic Queue

---

# 4. Priority Queue

Elements are removed based on priority instead of insertion order.

Applications

- Dijkstra Algorithm
- Task Scheduling
- Heaps

---

# Comparison

| Queue Type | Removal |
|------------|---------|
| Simple Queue | FIFO |
| Circular Queue | FIFO |
| Deque | Both Ends |
| Priority Queue | Highest/Lowest Priority |

---

# Interview Tip

Understand the differences because interview problems often require selecting the appropriate queue type.