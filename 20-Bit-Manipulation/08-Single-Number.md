# 🔢 Single Number

---

# Problem

Given an array where every element appears twice except one, find the unique element.

---

# Brute Force

- Count frequency using HashMap.

Complexity

Time

```
O(n)
```

Space

```
O(n)
```

---

# Optimal Approach

Use XOR.

```java
int ans = 0;

for(int num : nums){

    ans ^= num;

}

return ans;
```

---

# Why XOR?

```
a ^ a = 0

0 ^ b = b
```

Duplicate numbers cancel each other.

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

Whenever every element appears twice except one,

↓

Think **XOR**.