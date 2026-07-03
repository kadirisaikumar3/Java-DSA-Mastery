# ❌ Brute Force Approach

---

# What is Brute Force?

Brute Force checks every possible subarray or substring without optimization.

It is easy to understand but inefficient for large inputs.

---

# Example

## Maximum Sum Subarray of Size K

```java
int max = Integer.MIN_VALUE;

for(int i = 0; i <= arr.length-k; i++){

    int sum = 0;

    for(int j = i; j < i+k; j++){

        sum += arr[j];

    }

    max = Math.max(max, sum);

}
```

---

# Complexity

Time

```
O(n × k)
```

---

# Drawbacks

- Recalculates window repeatedly
- Inefficient
- Doesn't scale

---

# Why Optimize?

Sliding Window removes unnecessary computations.

```
O(n × k)

↓

O(n)
```

---

# Interview Tip

Always explain the brute-force approach before introducing Sliding Window.