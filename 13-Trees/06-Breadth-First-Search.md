# 🌐 Breadth First Search (BFS)

---

# What is BFS?

BFS explores all nodes at the current level before moving to the next level.

It always uses a **Queue**.

---

# Algorithm

1. Insert Root into Queue.
2. Remove Front Node.
3. Visit Node.
4. Add Children.
5. Repeat until Queue becomes empty.

---

# Java Code

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

# Applications

- Level Order Traversal
- Shortest Path (Unweighted Graph)
- Minimum Depth
- Zigzag Traversal

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

# Interview Tip

If the question asks for the **shortest path in an unweighted tree or graph**, BFS is often the correct choice.