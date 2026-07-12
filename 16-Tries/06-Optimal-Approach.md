# 🚀 Optimal Approach

---

# What is the Optimal Approach?

Store all words in a Trie.

Each character is processed only once while traversing.

---

# Pattern

```
Root

↓

Character

↓

Character

↓

Character

↓

Word
```

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(L) |
| Search | O(L) |
| StartsWith | O(L) |
| Delete | O(L) |

---

# Advantages

- Fast Prefix Search
- Shared Prefix Storage
- Efficient Dictionary Operations

---

# Interview Tip

Whenever the question mentions:

- Prefix
- Dictionary
- Auto Complete
- Word Search

Think **Trie** first.