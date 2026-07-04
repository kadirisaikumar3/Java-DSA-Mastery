# ⚡ Better Approach

---

# What is a Better Approach?

Improve brute-force by reducing unnecessary comparisons or narrowing the search space.

---

# Example

Search in a Sorted Array

Instead of checking every element:

Use Binary Search.

---

# Example Code

```java
Arrays.sort(nums);

int left = 0;
int right = nums.length - 1;

while(left <= right){

    int mid = left + (right - left) / 2;

    if(nums[mid] == target)

        return mid;

    if(nums[mid] < target)

        left = mid + 1;

    else

        right = mid - 1;

}
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

# Interview Tip

Whenever the search space is sorted, Binary Search is usually the better approach.