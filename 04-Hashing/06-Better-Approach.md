# ⚡ Better Approach

---

# What is a Better Approach?

A Better Approach improves the brute-force solution by storing previously computed information.

HashMap and HashSet are the most common choices.

---

# Example 1

## Contains Duplicate

```java
HashSet<Integer> set = new HashSet<>();

for(int num : arr){

    if(set.contains(num))

        return true;

    set.add(num);

}

return false;
```

Time

```
O(n)
```

Space

```
O(n)
```

---

# Example 2

## Two Sum

Use HashMap.

```java
HashMap<Integer, Integer> map = new HashMap<>();

for(int i = 0; i < arr.length; i++){

    int complement = target - arr[i];

    if(map.containsKey(complement))

        return new int[]{map.get(complement), i};

    map.put(arr[i], i);

}
```

Time

```
O(n)
```

---

# Benefits

- Faster execution
- Cleaner logic
- Scales well

---

# Interview Tip

If repeated searching occurs, ask:

**"Can I store previous results in a HashMap?"**