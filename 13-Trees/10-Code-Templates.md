# ☕ Java Code Templates

---

# Tree Node

```java
class TreeNode{

    int val;

    TreeNode left;
    TreeNode right;

    TreeNode(int val){

        this.val = val;

    }

}
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

# Preorder

```java
void preorder(TreeNode root){

    if(root == null)

        return;

    System.out.print(root.val + " ");

    preorder(root.left);

    preorder(root.right);

}
```

---

# Inorder

```java
void inorder(TreeNode root){

    if(root == null)

        return;

    inorder(root.left);

    System.out.print(root.val + " ");

    inorder(root.right);

}
```

---

# Postorder

```java
void postorder(TreeNode root){

    if(root == null)

        return;

    postorder(root.left);

    postorder(root.right);

    System.out.print(root.val + " ");

}
```

---

# Level Order

```java
Queue<TreeNode> queue = new LinkedList<>();

queue.offer(root);

while(!queue.isEmpty()){

    TreeNode node = queue.poll();

    if(node.left != null)
        queue.offer(node.left);

    if(node.right != null)
        queue.offer(node.right);

}
```

---

# Interview Tip

Master these five templates.

Nearly every Binary Tree interview question builds upon them.