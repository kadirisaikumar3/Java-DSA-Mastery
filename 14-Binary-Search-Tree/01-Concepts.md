# 🌲 BST Concepts

---

# What is a Binary Search Tree?

A Binary Search Tree (BST) is a Binary Tree where every node satisfies:

```
Left Subtree < Root < Right Subtree
```

This rule must hold for every node.

---

# Example

```
          8
        /   \
       3     10
      / \      \
     1   6      14
        / \     /
       4   7   13
```

---

# Characteristics

- Ordered Tree
- No Duplicate Values (generally)
- Efficient Searching
- Recursive Structure

---

# Advantages

- Fast Search
- Fast Insert
- Fast Delete
- Sorted Traversal using Inorder

---

# Disadvantages

- Can become skewed
- Worst-case performance becomes O(n)

---

# Complexity (Balanced BST)

| Operation | Time |
|-----------|------|
| Search | O(log n) |
| Insert | O(log n) |
| Delete | O(log n) |

---

# Interview Tip

Always remember the BST Rule:

```
Left < Root < Right
```