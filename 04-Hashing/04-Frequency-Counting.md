# 📊 Frequency Counting

---

# What is Frequency Counting?

Frequency Counting is a technique used to count how many times each element appears in a collection.

It is one of the most common applications of HashMap.

---

# Example

Array

```
[2, 3, 2, 5, 3, 2]
```

Frequency

```
2 → 3

3 → 2

5 → 1
```

---

# Java Implementation

```java
HashMap<Integer, Integer> map = new HashMap<>();

for(int num : arr){

    map.put(num, map.getOrDefault(num, 0) + 1);

}

System.out.println(map);
```

---

# Character Frequency

```java
HashMap<Character, Integer> map = new HashMap<>();

for(char ch : str.toCharArray()){

    map.put(ch, map.getOrDefault(ch, 0) + 1);

}
```

---

# Applications

- Count Duplicates
- Majority Element
- Valid Anagram
- Top K Frequent Elements
- Character Counting

---

# Complexity

| Operation | Time |
|-----------|------|
| Build Frequency Map | O(n) |
| Lookup | O(1) |

---

# Interview Tip

Whenever a problem asks **"How many times?"**, think **HashMap + Frequency Counting**.