# ➡️ Same Direction Pointers

---

# What are Same Direction Pointers?

Both pointers move from left to right.

Usually:

- Slow Pointer
- Fast Pointer

---

# Visualization

```
S → 1 2 3 4 5

F →→→→
```

---

# Example

## Remove Duplicates

```java
int slow = 0;

for(int fast = 1; fast < nums.length; fast++){

    if(nums[fast] != nums[slow]){

        slow++;

        nums[slow] = nums[fast];

    }

}

return slow + 1;
```

---

# Common Problems

- Remove Duplicates
- Move Zeroes
- Merge Sorted Arrays
- Partition Array

---

# Complexity

| Operation | Time |
|-----------|------|
| Traversal | O(n) |

---

# Interview Tip

Use Same Direction pointers when modifying arrays in-place or maintaining a valid subarray.