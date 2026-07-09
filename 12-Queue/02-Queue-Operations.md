# ⚙️ Queue Operations

---

# Enqueue

Adds an element at the rear of the queue.

```
10

20

↓

Enqueue(30)

↓

10

20

30
```

---

# Dequeue

Removes the front element.

```
10

20

30

↓

Dequeue()

↓

20

30
```

---

# Front

Returns the first element without removing it.

---

# Rear

Returns the last element.

---

# Java Example

```java
Queue<Integer> queue = new LinkedList<>();

queue.offer(10);
queue.offer(20);
queue.offer(30);

System.out.println(queue.peek());

queue.poll();
```

---

# Complexity

| Operation | Complexity |
|-----------|------------|
| Enqueue | O(1) |
| Dequeue | O(1) |
| Peek | O(1) |

---

# Interview Tip

Use `offer()` and `poll()` instead of `add()` and `remove()` for safer Queue operations in Java.