# 🌊 Level Order Traversal (BFS)

---

# What is Level Order Traversal?

Level Order Traversal visits nodes level by level from top to bottom.

It uses a **Queue** and is also known as **Breadth First Search (BFS)**.

---

# Example

```
        1
      /   \
     2     3
    / \   / \
   4  5  6  7
```

Traversal

```
1

2 3

4 5 6 7
```

Output

```
1 2 3 4 5 6 7
```

---

# Java Code

```java
Queue<TreeNode> queue = new LinkedList<>();

queue.offer(root);

while(!queue.isEmpty()){

    TreeNode node = queue.poll();

    System.out.print(node.val + " ");

    if(node.left != null)
        queue.offer(node.left);

    if(node.right != null)
        queue.offer(node.right);

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
O(n)
```

---

# Applications

- Binary Tree Level Order Traversal
- Right Side View
- Zigzag Traversal
- Minimum Depth
- BFS Problems

---

# Interview Tip

Whenever the problem mentions **level-by-level**, think **Queue (BFS)**.