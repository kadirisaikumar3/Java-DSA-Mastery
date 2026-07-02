# 🐢⚡ Fast and Slow Pointers

---

# What are Fast & Slow Pointers?

Fast and Slow Pointers (also called Floyd's Cycle Detection) use two pointers moving at different speeds.

- Slow Pointer → Moves one step
- Fast Pointer → Moves two steps

---

# Visualization

```
Slow → 1 → 2 → 3 → 4 → 5

Fast → 1 →→ 3 →→ 5
```

---

# Example

## Detect Cycle in Linked List

```java
ListNode slow = head;
ListNode fast = head;

while(fast != null && fast.next != null){

    slow = slow.next;

    fast = fast.next.next;

    if(slow == fast)

        return true;

}

return false;
```

---

# Applications

- Detect Cycle
- Find Middle Node
- Happy Number
- Circular Arrays

---

# Complexity

| Operation | Time |
|-----------|------|
| Traversal | O(n) |

---

# Interview Tip

Whenever the problem involves cycles or linked lists, consider Fast & Slow Pointers.