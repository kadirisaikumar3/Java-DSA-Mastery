# ❌ Brute Force Approach

---

# What is Brute Force?

Brute Force is the most straightforward way to solve a problem without worrying about optimization.

It is often the first approach discussed during coding interviews.

---

# Why Learn Brute Force?

- Builds intuition
- Helps verify correctness
- Serves as a baseline for optimization

---

# Example 1

## Find Maximum Element

Approach

Traverse the entire array and keep track of the maximum element.

Time Complexity

```
O(n)
```

Space Complexity

```
O(1)
```

---

# Example 2

## Two Sum

Approach

Use two nested loops to check every possible pair.

```java
for(int i=0;i<n;i++){
    for(int j=i+1;j<n;j++){
        if(arr[i]+arr[j]==target){
            // Pair Found
        }
    }
}
```

Time Complexity

```
O(n²)
```

Space Complexity

```
O(1)
```

---

# Example 3

## Maximum Subarray

Generate all possible subarrays and calculate their sums.

Time Complexity

```
O(n³)
```

---

# Why Optimize?

As input size grows, brute-force solutions become too slow.

Example:

```
n = 100000
```

An O(n²) solution performs billions of operations.

---

# Interview Tip

Always explain the brute-force approach first, then optimize it step by step. This demonstrates clear problem-solving skills and is appreciated by interviewers.