# ❌ Brute Force Approach

---

# What is Brute Force?

A Brute Force solution solves queue problems without using specialized queue structures.

It often results in unnecessary shifting or repeated traversals.

---

# Example

Insert an element into an array-based queue.

```
Before

10 20 30

↓

Insert 40

↓

10 20 30 40
```

Removing the front element requires shifting every remaining element.

---

# Java Example

```java
int[] queue = new int[100];
int size = 3;

// Remove front element
for(int i = 1; i < size; i++){

    queue[i - 1] = queue[i];

}

size--;
```

---

# Complexity

| Operation | Time |
|-----------|------|
| Enqueue | O(1) |
| Dequeue | O(n) |

---

# Drawbacks

- Element shifting
- Poor scalability
- Inefficient memory usage

---

# Interview Tip

Always explain the brute-force approach before introducing Circular Queue or Deque.