# 📏 Fixed Size Window

---

# What is a Fixed Size Window?

The window size remains constant throughout the algorithm.

---

# Example

Window Size = 3

```
[1 2 3] 4 5

↓

1 [2 3 4] 5

↓

1 2 [3 4 5]
```

---

# Algorithm

1. Build first window.
2. Calculate result.
3. Remove left element.
4. Add right element.
5. Repeat.

---

# Java Example

```java
int sum = 0;

for(int i = 0; i < k; i++)
    sum += arr[i];

int max = sum;

for(int i = k; i < arr.length; i++){

    sum += arr[i];

    sum -= arr[i-k];

    max = Math.max(max, sum);

}
```

---

# Applications

- Maximum Sum Subarray
- Average of Subarrays
- Fixed Window Statistics

---

# Complexity

Time

```
O(n)
```

Space

```
O(1)
```

---

# Interview Tip

If the window size is given in the problem statement, think Fixed Size Window.