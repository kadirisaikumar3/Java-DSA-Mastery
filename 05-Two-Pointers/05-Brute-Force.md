# ❌ Brute Force Approach

---

# What is Brute Force?

Brute Force checks every possible solution without optimization.

---

# Example

## Two Sum II

```java
for(int i = 0; i < nums.length; i++){

    for(int j = i + 1; j < nums.length; j++){

        if(nums[i] + nums[j] == target)

            return new int[]{i, j};

    }

}
```

---

# Time Complexity

```
O(n²)
```

---

# Drawbacks

- Nested loops
- Slow for large inputs
- Not scalable

---

# Why Optimize?

Two Pointer technique often reduces:

```
O(n²)

↓

O(n)
```

---

# Interview Tip

Always explain the brute-force solution first, then optimize using Two Pointers.