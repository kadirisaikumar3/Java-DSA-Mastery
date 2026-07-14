# ☕ Java Code Templates

---

# Activity Selection

```java
Arrays.sort(intervals,
(a,b) -> Integer.compare(a[1], b[1]));

int count = 1;
int end = intervals[0][1];

for(int i = 1; i < intervals.length; i++){

    if(intervals[i][0] >= end){

        count++;

        end = intervals[i][1];

    }

}
```

---

# Jump Game

```java
int reach = 0;

for(int i = 0; i < nums.length; i++){

    if(i > reach)

        return false;

    reach = Math.max(reach, i + nums[i]);

}

return true;
```

---

# Fractional Knapsack

```java
Arrays.sort(items,
(a,b) -> Double.compare(
b.value/(double)b.weight,
a.value/(double)a.weight
));
```

---

# Interview Tip

Most Greedy solutions begin with:

- Sorting
- Linear Traversal
- Local Best Choice