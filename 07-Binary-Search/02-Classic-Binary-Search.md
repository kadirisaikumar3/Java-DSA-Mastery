# 🔍 Classic Binary Search

---

# Algorithm

1. Initialize

```
left = 0

right = n-1
```

2. Find Middle

```
mid = left + (right-left)/2
```

3. Compare

- Equal → Return
- Smaller → Search Right
- Greater → Search Left

---

# Java Code

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

Time

```
O(log n)
```

Space

```
O(1)
```

---

# Applications

- Search Element
- Search Insert Position
- First Bad Version

---

# Interview Tip

Always calculate mid as

```java
left + (right-left)/2
```

to avoid integer overflow.