# 🏗️ Building a Segment Tree

---

# Idea

Recursively divide the array into two halves until each segment contains one element.

---

# Algorithm

1. Start with the full array.
2. Split into left and right halves.
3. Recursively build both halves.
4. Merge child results into the parent.

---

# Java Template

```java
void build(int node, int start, int end){

    if(start == end){

        tree[node] = arr[start];

        return;

    }

    int mid = (start + end) / 2;

    build(2 * node, start, mid);

    build(2 * node + 1, mid + 1, end);

    tree[node] = tree[2 * node] + tree[2 * node + 1];

}
```

---

# Complexity

Build Time

```
O(n)
```

Space

```
O(4n)
```

---

# Interview Tip

Although the tree is built recursively, each array element is processed only once, making the overall build time **O(n)**.