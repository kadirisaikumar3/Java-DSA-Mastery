# 🔄 Tree Traversals

---

# What is Tree Traversal?

Traversal means visiting every node exactly once.

---

# Types of Traversals

## Depth First Search (DFS)

- Preorder
- Inorder
- Postorder

---

## Breadth First Search (BFS)

- Level Order Traversal

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
      1
     / \
    2   3

Preorder

1 2 3
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
2 1 3
```

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
2 3 1
```

---

# Complexity

All traversals

Time

```
O(n)
```

Space

```
O(h)

h = Tree Height
```

---

# Interview Tip

Remember the traversal orders:

- **Preorder → Root Left Right**
- **Inorder → Left Root Right**
- **Postorder → Left Right Root**