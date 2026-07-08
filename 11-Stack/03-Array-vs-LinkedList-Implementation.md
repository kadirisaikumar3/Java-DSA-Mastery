# ⚖️ Array vs Linked List Implementation

---

# Stack Using Array

Stores elements in contiguous memory.

Advantages

- Faster cache performance
- Simple implementation

Disadvantages

- Fixed size (unless dynamically resized)

---

# Stack Using Linked List

Stores elements as linked nodes.

Advantages

- Dynamic size
- No resizing required

Disadvantages

- Extra memory for pointers

---

# Comparison

| Feature | Array | Linked List |
|---------|-------|-------------|
| Memory | Contiguous | Dynamic |
| Resize | Required | Not Required |
| Push | O(1) | O(1) |
| Pop | O(1) | O(1) |
| Extra Memory | No | Yes |

---

# When to Use?

Array

- Known size
- Better cache locality

Linked List

- Unknown size
- Frequent dynamic growth

---

# Interview Tip

In Java, `Stack` is available, but for interview coding many developers prefer using `Deque` (such as `ArrayDeque`) because it is generally faster and recommended for stack behavior.