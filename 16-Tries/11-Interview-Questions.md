# 🎯 Interview Questions

---

# Beginner

### 1. What is a Trie?

A Trie (Prefix Tree) is a tree-based data structure used to efficiently store and search strings using prefixes.

---

### 2. What is the Time Complexity of Trie operations?

| Operation | Time |
|-----------|------|
| Insert | O(L) |
| Search | O(L) |
| StartsWith | O(L) |
| Delete | O(L) |

L = Length of the word.

---

### 3. What does each Trie node store?

- Child pointers
- End-of-word flag

---

### 4. What is StartsWith?

It checks whether any word in the Trie begins with a given prefix.

---

### 5. What is the difference between Search and StartsWith?

- Search → Checks whether the complete word exists.
- StartsWith → Checks only whether the prefix exists.

---

# Intermediate

### 6. Why is Trie faster than brute force for prefix search?

Because it processes each character only once without scanning every stored word.

---

### 7. What is the biggest disadvantage of Trie?

Higher memory usage due to storing child pointers for each node.

---

### 8. What is a Binary Trie?

A Trie that stores binary digits (0 and 1), commonly used in Maximum XOR problems.

---

### 9. Can duplicate words exist?

Yes, but implementations usually maintain a count or simply mark the end of a word.

---

### 10. Where are Tries used?

- Search Engines
- Auto Complete
- Spell Checker
- Dictionary
- IP Routing

---

# Google-Level Questions

- Implement Trie
- Word Search II
- Search Suggestions System
- Replace Words
- Maximum XOR

---

# Interview Tip

Always explain:

- Trie Node Structure
- Character Traversal
- Time & Space Complexity