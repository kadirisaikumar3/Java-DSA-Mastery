# ↔️ Opposite Direction Pointers

---

# What are Opposite Direction Pointers?

Two pointers start from opposite ends of the array or string and move toward each other.

---

# Visualization

```
L → 1 2 3 4 5 ← R
```

---

# Movement

- Left Pointer moves right
- Right Pointer moves left

---

# Example

## Valid Palindrome

```java
while(left < right){

    if(s.charAt(left) != s.charAt(right))

        return false;

    left++;

    right--;

}

return true;
```

---

# Common Problems

- Valid Palindrome
- Two Sum II
- Container With Most Water
- Trapping Rain Water
- Reverse String

---

# Complexity

| Operation | Time |
|-----------|------|
| Traversal | O(n) |

---

# Interview Tip

Opposite Direction pointers work best on sorted arrays and palindrome-based problems.