# 🌲 Depth First Search (DFS)

---

# What is DFS?

DFS explores one branch completely before moving to another.

DFS is usually implemented using **Recursion** or a **Stack**.

---

# DFS Types

- Preorder
- Inorder
- Postorder

---

# Example

```
        1
      /   \
     2     3
    / \
   4   5
```

Preorder

```
1 2 4 5 3
```

Inorder

```
4 2 5 1 3
```

Postorder

```
4 5 2 3 1
```

---

# Recursive DFS

```java
void dfs(TreeNode root){

    if(root == null)
        return;

    dfs(root.left);

    dfs(root.right);

}
```

---

# Complexity

Time

```
O(n)
```

Space

```
O(h)
```

where **h = height of the tree**.

---

# Interview Tip

Most Tree interview questions use **Recursive DFS**.