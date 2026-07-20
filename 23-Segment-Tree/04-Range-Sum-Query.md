# ➕ Range Sum Query

---

# Purpose

A Range Sum Query returns the sum of elements within a given interval.

---

# Example

Array

```
[2, 5, 1, 4, 3]
```

Query

```
Sum(1,3)
```

Result

```
5 + 1 + 4 = 10
```

---

# Java Template

```java
int query(int node, int start, int end, int left, int right){

    if(right < start || end < left)
        return 0;

    if(left <= start && end <= right)
        return tree[node];

    int mid = (start + end) / 2;

    return query(2 * node, start, mid, left, right)
         + query(2 * node + 1, mid + 1, end, left, right);

}
```

---

# Complexity

```
O(log n)
```

---

# Interview Tip

Avoid traversing the entire array. Segment Trees answer range sum queries efficiently using only the required segments.