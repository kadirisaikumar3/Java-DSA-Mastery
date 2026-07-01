# 🗂 HashMap

---

# What is HashMap?

HashMap stores data as

```
Key → Value
```

Each key must be unique.

---

# Declaration

```java
HashMap<Integer,String> map = new HashMap<>();
```

---

# Insert

```java
map.put(1,"Java");
```

---

# Get

```java
map.get(1);
```

---

# Contains Key

```java
map.containsKey(1);
```

---

# Remove

```java
map.remove(1);
```

---

# Iterate

```java
for(Map.Entry<Integer,String> entry : map.entrySet()){

    System.out.println(entry.getKey()+" "+entry.getValue());

}
```

---

# Complexity

| Operation | Time |
|-----------|------|
| put() | O(1) |
| get() | O(1) |
| remove() | O(1) |
| containsKey() | O(1) |

---

# Applications

- Frequency Counting
- Caching
- Graphs
- Dynamic Programming
- Memoization

---

# Interview Tip

HashMap is the first data structure to consider for fast lookups.