# 🔄 BST Traversals

---

# What are BST Traversals?

Traversal means visiting every node exactly once.

The traversal methods are the same as Binary Trees.

---

# Preorder

```
Root

↓

Left

↓

Right
```

Example

```
      5
     / \
    3   7

Preorder

5 3 7
```

---

# Inorder

```
Left

↓

Root

↓

Right
```

Example

```
3 5 7
```

✅ In a BST, Inorder Traversal always produces elements in **sorted order**.

---

# Postorder

```
Left

↓

Right

↓

Root
```

Example

```
3 7 5
```

---

# Complexity

| Traversal | Time |
|-----------|------|
| Preorder | O(n) |
| Inorder | O(n) |
| Postorder | O(n) |

---

# Interview Tip

If a question asks for elements in sorted order from a BST,

think:

**Inorder Traversal**