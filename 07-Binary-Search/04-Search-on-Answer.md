# 🔍 Search on Answer

---

# What is Search on Answer?

Search on Answer is a Binary Search technique where we search for the optimal answer instead of an element.

The answer space is monotonic, allowing Binary Search.

---

# Example

Question:

Find the minimum eating speed for Koko to finish bananas in H hours.

Search Space

```
1 ........ MaxPile
```

Instead of checking every speed, Binary Search finds the minimum valid speed.

---

# General Steps

1. Define search space.
2. Calculate middle answer.
3. Check if it is valid.
4. If valid, search left.
5. Otherwise, search right.

---

# Java Template

```java
int left = 1;
int right = maxValue;

while(left < right){

    int mid = left + (right - left) / 2;

    if(isPossible(mid)){

        right = mid;

    }else{

        left = mid + 1;

    }

}

return left;
```

---

# Applications

- Koko Eating Bananas
- Capacity to Ship Packages
- Split Array Largest Sum
- Minimum Days to Make Bouquets

---

# Complexity

Time

```
O(log n × Check Function)
```

---

# Interview Tip

Whenever you need the **minimum** or **maximum** feasible value, think **Search on Answer**.