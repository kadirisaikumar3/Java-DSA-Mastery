# 🚀 Optimal Approach

---

# What is the Optimal Approach?

Efficient Linked List solutions use pointer manipulation to minimize traversals.

---

# Common Techniques

- Fast & Slow Pointer
- Dummy Node
- Two Pointers
- In-place Reversal

---

# Example

Reverse Linked List

```java
Node prev = null;
Node current = head;

while(current != null){

    Node next = current.next;

    current.next = prev;

    prev = current;

    current = next;

}

head = prev;
```

---

# Complexity

| Operation | Time | Space |
|-----------|------|-------|
| Reverse | O(n) | O(1) |
| Find Middle | O(n) | O(1) |
| Detect Cycle | O(n) | O(1) |

---

# Advantages

- Single Traversal
- Constant Extra Space
- Interview Preferred

---

# Interview Tip

Minimize the number of passes through the linked list whenever possible.