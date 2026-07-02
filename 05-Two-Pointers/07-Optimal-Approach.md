# 🚀 Optimal Approach

---

# What is an Optimal Approach?

The Optimal Approach solves the problem using the best possible Time and Space Complexity.

---

# Example

## Two Sum II (Sorted Array)

```java
int left = 0;
int right = nums.length - 1;

while(left < right){

    int sum = nums[left] + nums[right];

    if(sum == target)

        return new int[]{left, right};

    if(sum < target)

        left++;

    else

        right--;

}

return new int[]{-1, -1};
```

---

# Complexity

| Metric | Value |
|--------|-------|
| Time | O(n) |
| Space | O(1) |

---

# Benefits

- Fastest solution
- Constant extra space
- Simple implementation

---

# Interview Tip

Always explain why pointer movement guarantees that no valid solution is skipped.