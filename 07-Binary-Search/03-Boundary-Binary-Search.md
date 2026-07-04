# 🎯 Boundary Binary Search

---

# What is Boundary Binary Search?

Boundary Binary Search finds the first or last occurrence of an element instead of any occurrence.

---

# Types

- First Occurrence
- Last Occurrence
- Lower Bound
- Upper Bound

---

# Example

Array

```
1 2 2 2 3 4
```

Target

```
2
```

Answer

```
First = 1

Last = 3
```

---

# Java Template

```java
while(left <= right){

    int mid = left + (right-left)/2;

    if(arr[mid] >= target){

        answer = mid;

        right = mid - 1;

    }else{

        left = mid + 1;

    }

}
```

---

# Complexity

Time

```
O(log n)
```

---

# Applications

- Lower Bound
- Upper Bound
- Count Occurrences
- First & Last Position

---

# Interview Tip

Don't stop after finding the target.

Continue searching to locate the required boundary.