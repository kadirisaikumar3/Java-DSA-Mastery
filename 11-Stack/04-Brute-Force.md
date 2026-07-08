# ❌ Brute Force Approach

---

# What is Brute Force?

A Brute Force solution solves the problem directly without using Stack optimization.

It usually involves multiple traversals or nested loops.

---

# Example

Find the Next Greater Element

Array

```
[2, 1, 5, 3]
```

For each element, scan to the right until a greater element is found.

---

# Java Example

```java
for(int i = 0; i < nums.length; i++){

    for(int j = i + 1; j < nums.length; j++){

        if(nums[j] > nums[i]){

            System.out.println(nums[j]);
            break;

        }

    }

}
```

---

# Complexity

| Operation | Time |
|-----------|------|
| Next Greater Element | O(n²) |
| Daily Temperatures | O(n²) |

---

# Drawbacks

- Nested loops
- Repeated comparisons
- Poor performance on large inputs

---

# Interview Tip

Always explain the brute-force solution before optimizing with a Stack.