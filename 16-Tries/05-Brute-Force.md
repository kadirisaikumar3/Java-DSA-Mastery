# ❌ Brute Force Approach

---

# What is Brute Force?

Store all words in an array or list.

For every search or prefix query, compare each stored word.

---

# Example

Words

```
apple
apply
apt
bat
```

Search Prefix

```
ap
```

Check every word one by one.

---

# Complexity

Insert

```
O(1)
```

Search

```
O(n × L)
```

Prefix Search

```
O(n × L)
```

---

# Drawbacks

- Slow Prefix Search
- Inefficient for large dictionaries
- Repeated comparisons

---

# Interview Tip

If the problem contains many prefix searches, avoid brute force and think of a Trie.