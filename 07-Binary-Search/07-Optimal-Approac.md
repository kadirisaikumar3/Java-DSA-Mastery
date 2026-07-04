# 🚀 Optimal Approach

---

# What is the Optimal Approach?

The Optimal Approach minimizes the search space by half after every comparison.

---

# Example

Classic Binary Search

```java
int left = 0;
int right = arr.length - 1;

while(left <= right){

    int mid = left + (right - left) / 2;

    if(arr[mid] == target)

        return mid;

    if(arr[mid] < target)

        left = mid + 1;

    else

        right = mid - 1;

}

return -1;
```

---

# Complexity

| Metric | Value |
|---------|-------|
| Time | O(log n) |
| Space | O(1) |

---

# Advantages

- Fastest search
- Constant memory
- Handles very large datasets efficiently

---

# Interview Tip

Whenever you discard half of the search space in each iteration, explain why the discarded half can never contain the answer.