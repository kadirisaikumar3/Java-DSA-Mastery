# 📋 Subset Generation

---

# Idea

Every subset can be represented using a bitmask.

---

# Example

```
nums = [1,2,3]
```

Total Subsets

```
2³ = 8
```

Masks

```
000

001

010

011

100

101

110

111
```

---

# Java Template

```java
for(int mask = 0; mask < (1 << n); mask++){

    for(int i = 0; i < n; i++){

        if((mask & (1 << i)) != 0){

            // include nums[i]

        }

    }

}
```

---

# Complexity

Time

```
O(n × 2ⁿ)
```

---

# Interview Tip

Subset generation using bitmasks is a classic interview pattern.