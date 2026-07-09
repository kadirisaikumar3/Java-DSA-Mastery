# ☕ Java Code Templates

---

# Queue

```java
Queue<Integer> queue = new LinkedList<>();

queue.offer(10);
queue.offer(20);

System.out.println(queue.peek());

queue.poll();
```

---

# ArrayDeque

```java
Deque<Integer> deque = new ArrayDeque<>();

deque.offerLast(10);
deque.offerLast(20);

deque.pollFirst();
```

---

# Priority Queue (Min Heap)

```java
PriorityQueue<Integer> pq = new PriorityQueue<>();

pq.offer(30);
pq.offer(10);
pq.offer(20);

System.out.println(pq.poll());
```

---

# Max Heap

```java
PriorityQueue<Integer> maxHeap =
    new PriorityQueue<>(Collections.reverseOrder());
```

---

# BFS Template

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

For normal queue operations, prefer `ArrayDeque` over `LinkedList` in Java unless you specifically need `null` elements or LinkedList features.