# ☕ Java Code Templates

---

# Create HashMap

```java
HashMap<Integer, Integer> map = new HashMap<>();
```

---

# Insert Element

```java
map.put(10, 1);
```

---

# Get Value

```java
int value = map.get(10);
```

---

# Get Default Value

```java
int count = map.getOrDefault(10, 0);
```

---

# Check Key

```java
if(map.containsKey(10)){

    System.out.println("Found");

}
```

---

# Remove Key

```java
map.remove(10);
```

---

# Iterate HashMap

```java
for(Map.Entry<Integer,Integer> entry : map.entrySet()){

    System.out.println(entry.getKey() + " -> " + entry.getValue());

}
```

---

# Create HashSet

```java
HashSet<Integer> set = new HashSet<>();
```

---

# Insert into HashSet

```java
set.add(20);
```

---

# Search in HashSet

```java
set.contains(20);
```

---

# Remove from HashSet

```java
set.remove(20);
```

---

# Frequency Counting

```java
HashMap<Integer,Integer> freq = new HashMap<>();

for(int num : arr){

    freq.put(num, freq.getOrDefault(num,0)+1);

}
```

---

# Interview Tip

Practice these templates until you can write them from memory.