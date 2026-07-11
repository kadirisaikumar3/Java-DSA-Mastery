# 📏 BST Properties

---

# Main Property

For every node:

```
Left Subtree

↓

Smaller Values

↓

Root

↓

Greater Values

↓

Right Subtree
```

---

# Inorder Traversal

The Inorder Traversal of a BST always produces a sorted sequence.

Example

```
        5
      /   \
     3     7
    / \   / \
   2  4  6  8
```

Inorder

```
2 3 4 5 6 7 8
```

---

# Minimum Value

Keep moving left until NULL.

---

# Maximum Value

Keep moving right until NULL.

---

# Balanced vs Skewed BST

Balanced BST

```
Height = O(log n)
```

Skewed BST

```
Height = O(n)
```

---

# Interview Tip

If Inorder Traversal is not sorted,

the Tree is **not** a valid BST.