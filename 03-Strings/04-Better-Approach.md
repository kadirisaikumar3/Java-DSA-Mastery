# ⚡ Better Approach

---

# What is a Better Approach?

A Better Approach improves the brute-force solution by using efficient data structures or algorithms while maintaining correctness.

The goal is to reduce unnecessary operations and improve scalability.

---

# Common Optimization Techniques

- Frequency Array
- HashMap
- HashSet
- StringBuilder
- Two Pointers
- Sliding Window

---

# Example 1

## Valid Anagram

### Brute Force

Sort both strings.

```
Time

O(n log n)
```

### Better Approach

Use a frequency array.

```java
int[] freq = new int[26];

for(char ch : s.toCharArray())
    freq[ch-'a']++;

for(char ch : t.toCharArray())
    freq[ch-'a']--;

for(int count : freq)
    if(count != 0)
        return false;

return true;
```

Time

```
O(n)
```

Space

```
O(1)
```

---

# Example 2

Character Frequency

Use HashMap for Unicode characters.

```
Time

O(n)
```

---

# Example 3

Reverse Words

Use StringBuilder instead of repeated string concatenation.

---

# Benefits

- Faster execution
- Cleaner code
- Better interview performance

---

# Interview Tip

Whenever you see repeated searching or sorting, ask yourself:

"Can a HashMap or Frequency Array reduce the complexity?"