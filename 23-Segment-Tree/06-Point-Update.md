# ✏️ Point Update

---

# Purpose

Update a single array element and reflect the change throughout the Segment Tree.

---

# Example

Array

```
[2, 5, 1, 4]
```

Update

```
arr[2] = 8
```

Updated Array

```
[2, 5, 8, 4]
```

---

# Java Template

```java
void update(int node, int start, int end, int index, int value){

    if(start == end){

        tree[node] = value;

        return;

    }

    int mid = (start + end) / 2;

    if(index <= mid)
        update(2 * node, start, mid, index, value);
    else
        update(2 * node + 1, mid + 1, end, index, value);

    tree[node] = tree[2 * node] + tree[2 * node + 1];

}
```

---

# Complexity

```
O(log n)
```

---

# Interview Tip

Only nodes on the path from the updated leaf to the root need to be recalculated.