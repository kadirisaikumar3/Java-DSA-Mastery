# 📖 Linked List Concepts

---

# What is a Linked List?

A Linked List is a collection of nodes connected using references (pointers).

Each node stores:

- Data
- Reference to the next node

---

# Visualization

```
Head

↓

+------+-----+     +------+-----+     +------+------+
|  10  |  ●──┼────►|  20  |  ●──┼────►|  30  | NULL |
+------+-----+     +------+-----+     +------+------+
```

---

# Node Structure

```java
class Node{

    int data;

    Node next;

    Node(int data){

        this.data = data;
        this.next = null;

    }

}
```

---

# Advantages

- Dynamic Size
- Efficient Insertions
- Efficient Deletions
- Memory Efficient

---

# Disadvantages

- Sequential Access
- Extra Memory for Pointers
- Slower Search

---

# Complexity

| Operation | Time |
|-----------|------|
| Access | O(n) |
| Search | O(n) |
| Insert at Head | O(1) |
| Delete at Head | O(1) |

---

# Interview Tip

Arrays provide fast access.

Linked Lists provide fast insertions and deletions.