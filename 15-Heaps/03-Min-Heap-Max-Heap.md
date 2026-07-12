# ⚖️ Min Heap vs Max Heap

---

# Min Heap

Root contains the smallest element.

Applications

- Dijkstra's Algorithm
- Merge K Sorted Lists
- K Closest Points

---

# Max Heap

Root contains the largest element.

Applications

- Kth Largest Element
- Heap Sort
- Priority Scheduling

---

# Comparison

| Feature | Min Heap | Max Heap |
|---------|----------|----------|
| Root | Smallest | Largest |
| Priority | Minimum | Maximum |
| Peek | O(1) | O(1) |
| Insert | O(log n) | O(log n) |
| Delete | O(log n) | O(log n) |

---

# Java

Min Heap

```java
PriorityQueue<Integer> minHeap = new PriorityQueue<>();
```

Max Heap

```java
PriorityQueue<Integer> maxHeap =
    new PriorityQueue<>(Collections.reverseOrder());
```

---

# Interview Tip

Java's `PriorityQueue` implements a **Min Heap** by default.