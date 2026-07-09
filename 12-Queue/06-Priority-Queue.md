# ⭐ Priority Queue

---

# What is a Priority Queue?

A Priority Queue removes elements based on priority rather than insertion order.

In Java, it is implemented using a Heap.

---

# Example

```
Elements

5

2

8

1

↓

Removal Order

1

2

5

8
```

(Min Heap)

---

# Java Example

```java
PriorityQueue<Integer> pq = new PriorityQueue<>();

pq.offer(5);
pq.offer(2);
pq.offer(8);

System.out.println(pq.poll());
```

---

# Applications

- Dijkstra Algorithm
- Huffman Coding
- Task Scheduling
- CPU Scheduling
- Top K Elements

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(log n) |
| Remove | O(log n) |
| Peek | O(1) |

---

# Interview Tip

Remember:

Java's `PriorityQueue` is a **Min Heap** by default.