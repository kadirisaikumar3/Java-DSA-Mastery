# 📖 Stack Concepts

---

# What is a Stack?

A Stack is a linear data structure that follows the Last In, First Out (LIFO) principle.

The last element inserted is the first element removed.

---

# Visualization

```

Top
│
▼
+-----+
| 30 |
+-----+
| 20 |
+-----+
| 10 |
+-----+

```

---

# LIFO Principle

```

Push 10

Push 20

Push 30

↓

Pop

30

↓

Pop

20

↓

Pop

10

```

---

# Basic Operations

- Push
- Pop
- Peek (Top)
- isEmpty()
- Size

---

# Advantages

- Fast insertion
- Fast deletion
- Simple implementation
- Efficient memory usage

---

# Disadvantages

- No random access
- Limited to top operations

---

# Complexity

| Operation | Time |
|-----------|------|
| Push | O(1) |
| Pop | O(1) |
| Peek | O(1) |

---

# Interview Tip

Whenever you need to process elements in reverse order,

Think:

**Stack**