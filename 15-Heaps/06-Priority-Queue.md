# ⭐ Priority Queue

---

# What is a Priority Queue?

A Priority Queue removes elements based on priority instead of insertion order.

In Java, it is implemented using a Heap.

---

# Java Min Heap

```java
PriorityQueue<Integer> pq = new PriorityQueue<>();

pq.offer(30);
pq.offer(10);
pq.offer(20);

System.out.println(pq.poll()); // 10
```

---

# Java Max Heap

```java
PriorityQueue<Integer> maxHeap =
    new PriorityQueue<>(Collections.reverseOrder());
```

---

# Applications

- Dijkstra's Algorithm
- Prim's Algorithm
- Task Scheduling
- Top K Problems
- Event Simulation

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(log n) |
| Remove | O(log n) |
| Peek | O(1) |

---

# Interview Tip

Remember: Java's `PriorityQueue` is a **Min Heap** by default.