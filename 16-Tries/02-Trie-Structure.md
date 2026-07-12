# 🌲 Trie Structure

---

# Trie Node

Each node stores

- Children
- End of Word Flag

---

# Java Structure

```java
class TrieNode{

    TrieNode[] children = new TrieNode[26];

    boolean isEnd;

}
```

---

# Visualization

```
Root

 |

 c

 |

 a

/ \

t  r
```

---

# Root Node

The root node does not store a character.

It only serves as the starting point.

---

# Children

Each child represents one character.

For lowercase English letters

```
26 children
```

---

# End of Word

A boolean flag indicates whether the current node marks the end of a valid word.

---

# Interview Tip

Every path from the root represents a prefix.