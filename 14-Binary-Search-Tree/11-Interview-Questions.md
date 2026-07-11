# 🎯 Interview Questions

---

# Beginner

### 1. What is a Binary Search Tree?

A Binary Search Tree (BST) is a Binary Tree where every node satisfies:

```
Left < Root < Right
```

---

### 2. Why is BST better than a normal Binary Tree?

Because searching, insertion, and deletion are more efficient in a balanced BST.

---

### 3. What is the Time Complexity of Search?

Balanced BST

```
O(log n)
```

Worst Case

```
O(n)
```

---

### 4. Why is Inorder Traversal important?

Because Inorder Traversal of a BST always produces a sorted sequence.

---

### 5. What is a Skewed BST?

A BST where every node has only one child, making it similar to a Linked List.

---

# Intermediate

### 6. How do you validate a BST?

Using recursive range validation or Inorder Traversal.

---

### 7. How do you find the minimum element?

Move continuously to the left until NULL.

---

### 8. How do you find the maximum element?

Move continuously to the right until NULL.

---

### 9. What are the deletion cases?

- Leaf Node
- One Child
- Two Children (Replace with Inorder Successor or Predecessor)

---

### 10. Why is BST search efficient?

Each comparison eliminates nearly half of the remaining search space in a balanced BST.

---

# Google-Level Questions

- Validate BST
- Kth Smallest Element
- BST Iterator
- Delete Node in BST
- Lowest Common Ancestor
- Recover BST

---

# Interview Tip

Always explain:

- BST Property
- Recursive Calls
- Time & Space Complexity