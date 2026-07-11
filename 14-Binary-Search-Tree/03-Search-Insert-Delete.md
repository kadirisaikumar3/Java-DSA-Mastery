# ⚙️ Search, Insert & Delete

---

# Search

Compare the target value with the current node.

- Smaller → Go Left
- Greater → Go Right
- Equal → Found

---

# Insert

Find the correct NULL position while maintaining the BST property.

---

# Delete Cases

## Case 1

Leaf Node

```
Delete directly.
```

---

## Case 2

One Child

Replace the node with its child.

---

## Case 3

Two Children

Replace with:

- Inorder Successor (Minimum in Right Subtree)

OR

- Inorder Predecessor (Maximum in Left Subtree)

---

# Complexity

| Operation | Balanced BST |
|-----------|--------------|
| Search | O(log n) |
| Insert | O(log n) |
| Delete | O(log n) |

Worst Case (Skewed BST)

```
O(n)
```

---

# Interview Tip

Deletion with two children is the most frequently asked BST operation in interviews.