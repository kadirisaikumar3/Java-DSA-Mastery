# 🚀 Optimal Approach

---

# What is the Optimal Approach?

Maintain a window and update it efficiently as elements enter and leave.

---

# Example

```java
int sum = 0;

for(int i=0;i<k;i++)
    sum += arr[i];

int max = sum;

for(int i=k;i<arr.length;i++){

    sum += arr[i];

    sum -= arr[i-k];

    max = Math.max(max,sum);

}
```

---

# Complexity

| Metric | Value |
|---------|-------|
| Time | O(n) |
| Space | O(1) |

---

# Advantages

- Linear traversal
- Constant memory
- Interview preferred

---

# Interview Tip

Always explain why only one element enters and one element leaves the window.