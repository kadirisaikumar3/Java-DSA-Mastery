# ☕ Java Code Templates

---

# Search

```java
TreeNode search(TreeNode root, int target){

    if(root == null || root.val == target)

        return root;

    if(target < root.val)

        return search(root.left, target);

    return search(root.right, target);

}
```

---

# Insert

```java
TreeNode insert(TreeNode root, int val){

    if(root == null)

        return new TreeNode(val);

    if(val < root.val)

        root.left = insert(root.left, val);

    else

        root.right = insert(root.right, val);

    return root;

}
```

---

# Find Minimum

```java
TreeNode minimum(TreeNode root){

    while(root.left != null)

        root = root.left;

    return root;

}
```

---

# Validate BST (Range Method)

```java
boolean isValid(TreeNode root,
                long min,
                long max){

    if(root == null)

        return true;

    if(root.val <= min || root.val >= max)

        return false;

    return isValid(root.left, min, root.val) &&
           isValid(root.right, root.val, max);

}
```

---

# Interview Tip

The **Range Validation** method is the preferred solution for validating a BST in interviews.