# ❌ Brute Force Approach

---

# What is Brute Force?

Brute Force is the simplest solution without optimization.

It helps verify correctness before improving efficiency.

---

# Example 1

Valid Anagram

Brute Force

Sort both strings.

```java
char[] a = s.toCharArray();

char[] b = t.toCharArray();

Arrays.sort(a);

Arrays.sort(b);

return Arrays.equals(a,b);
```

Time Complexity

```
O(n log n)
```

Space Complexity

```
O(n)
```

---

# Example 2

Longest Common Prefix

Compare every character across all strings.

Time

```
O(n*m)
```

---

# Example 3

Palindrome

Compare first and last characters.

Move inward.

Time

```
O(n)
```

---

# Why Optimize?

Sorting is often unnecessary.

Using frequency arrays or HashMaps can reduce complexity.

---

# Interview Tip

Always begin with the brute-force approach.

Then explain how to optimize it.

Interviewers value structured thinking more than memorized solutions.