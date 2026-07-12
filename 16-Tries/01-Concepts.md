# 🌳 Trie Concepts

---

# What is a Trie?

A Trie (Prefix Tree) is a tree data structure where each node represents one character.

Words sharing a common prefix also share the same path in the Trie.

---

# Example

Words

```
cat

car

can
```

Trie

```
      Root
       |
       c
       |
       a
     / | \
    t  r  n
```

---

# Characteristics

- Stores Strings
- Prefix Sharing
- Fast Search
- Recursive Structure

---

# Advantages

- Efficient Prefix Search
- Fast Insert
- Fast Search
- Saves space using shared prefixes

---

# Disadvantages

- Higher memory usage
- More pointers than arrays

---

# Complexity

| Operation | Time |
|-----------|------|
| Insert | O(L) |
| Search | O(L) |
| StartsWith | O(L) |

L = Length of the word

---

# Interview Tip

Trie problems usually involve searching many words with common prefixes.