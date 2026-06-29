# ⚡ Better Approach

---

# What is a Better Approach?

A Better Approach improves the brute-force solution by using additional data structures or preprocessing techniques.

The goal is to reduce Time Complexity while maintaining correctness.

---

# Common Optimization Techniques

- HashMap
- HashSet
- Prefix Sum
- Sorting
- Binary Search
- Two Pointers

---

# Example 1

## Two Sum

### Brute Force

Nested loops

```
Time: O(n²)
```

### Better Approach

Store visited elements in a HashMap.

```java
HashMap<Integer,Integer> map = new HashMap<>();

for(int i=0;i<arr.length;i++){

    int complement = target-arr[i];

    if(map.containsKey(complement)){

        System.out.println("Pair Found");

    }

    map.put(arr[i],i);

}
```

Time Complexity

```
O(n)
```

Space Complexity

```
O(n)
```

---

# Example 2

Subarray Sum Equals K

Technique

```
Prefix Sum + HashMap
```

Brute Force

```
O(n²)
```

Better

```
O(n)
```

---

# Benefits

- Faster execution
- Better scalability
- Interview-friendly

---

# Interview Tip

Whenever brute force uses nested loops,

Ask yourself:

"Can I store previously computed information?"