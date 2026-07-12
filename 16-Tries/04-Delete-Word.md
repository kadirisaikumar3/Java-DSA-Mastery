# 🗑️ Delete Word

---

# What is Delete?

Delete removes a word from the Trie while preserving other words that share the same prefix.

---

# Steps

1. Search for the word.
2. Unmark the end-of-word flag.
3. Remove unnecessary nodes from bottom to top.
4. Stop deleting if another word still uses the node.

---

# Example

Words

```
cat
car
```

Delete

```
cat
```

Remaining

```
car
```

The nodes `c` and `a` remain because they are shared.

---

# Complexity

| Operation | Time |
|-----------|------|
| Delete | O(L) |

L = Length of the word

---

# Interview Tip

Never delete shared prefix nodes that are required by other words.