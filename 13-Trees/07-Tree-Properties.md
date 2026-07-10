# 📏 Tree Properties

---

# Height

The number of edges on the longest path from the root to a leaf.

---

# Depth

The number of edges from the root to a node.

---

# Level

Root

```
Level 0
```

Children

```
Level 1
```

Grandchildren

```
Level 2
```

---

# Leaf Node

A node with no children.

---

# Internal Node

A node having at least one child.

---

# Height Formula

```
Height =

1 +

max(leftHeight,
    rightHeight)
```

---

# Java Example

```java
int height(TreeNode root){

    if(root == null)

        return 0;

    return 1 + Math.max(height(root.left),
                        height(root.right));

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

---

# Interview Tip

Questions involving **Height**, **Diameter**, **Balanced Tree**, and **Maximum Depth** all rely on recursive height calculations.