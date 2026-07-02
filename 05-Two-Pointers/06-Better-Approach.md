# ⚡ Better Approach

---

# What is a Better Approach?

A Better Approach improves the brute-force solution using problem-specific observations.

Sometimes sorting or additional data structures help.

---

# Example

## Pair Sum

Sort the array first.

Then apply Two Pointers.

---

# Example Code

```java
Arrays.sort(nums);

int left = 0;
int right = nums.length - 1;

while(left < right){

    int sum = nums[left] + nums[right];

    if(sum == target)

        break;

    if(sum < target)

        left++;

    else

        right--;

}
```

---

# Complexity

Sorting

```
O(n log n)
```

Traversal

```
O(n)
```

Overall

```
O(n log n)
```

---

# Interview Tip

If sorting is allowed, it often enables the Two Pointer technique.