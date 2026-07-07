# ❌ Brute Force Approach

---

# What is Brute Force?

A straightforward solution without using optimized pointer techniques.

---

# Example

Searching an element

```java
Node current = head;

while(current != null){

    if(current.data == target)
        return current;

    current = current.next;

}

return null;
```

---

# Complexity

| Operation | Time |
|-----------|------|
| Search | O(n) |
| Reverse | O(n) |
| Delete Tail | O(n) |

---

# Drawbacks

- Multiple Traversals
- Unnecessary Operations
- Slower for Large Lists

---

# Why Optimize?

Using pointer techniques:

```
Fast & Slow Pointer

↓

Single Traversal

↓

Better Performance
```

---

# Interview Tip

Start with a simple solution before introducing pointer optimization.