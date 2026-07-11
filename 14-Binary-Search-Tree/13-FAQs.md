# ❓ Frequently Asked Questions

---

## Q1. What is the difference between Binary Tree and BST?

A Binary Tree has no ordering rule.

A BST always satisfies:

```
Left < Root < Right
```

---

## Q2. Why is Inorder Traversal sorted?

Because BST stores smaller values in the left subtree and larger values in the right subtree.

---

## Q3. Can BST contain duplicate values?

Generally, duplicates are not allowed, although some implementations define a consistent rule for handling them.

---

## Q4. Why can BST become slow?

If it becomes skewed, operations degrade to O(n).

---

## Q5. Which validation method is preferred?

Recursive Range Validation.

---

## Q6. Which BST problems are most important?

- Validate BST
- Delete Node
- Kth Smallest
- BST Iterator
- Lowest Common Ancestor

---

## Q7. Biggest interview advice?

Always use the BST property before writing code. Never treat it like a normal Binary Tree.