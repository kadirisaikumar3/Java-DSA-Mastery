# ☕ Java Code Templates

---

# Fixed Size Window

```java
int sum = 0;

for(int i=0;i<k;i++)
    sum += arr[i];

for(int i=k;i<arr.length;i++){

    sum += arr[i];

    sum -= arr[i-k];

}
```

---

# Variable Size Window

```java
int left = 0;

for(int right=0; right<n; right++){

    while(condition){

        left++;

    }

}
```

---

# Longest Window

```java
int ans = 0;

while(condition){

    ans = Math.max(ans, right-left+1);

}
```

---

# Minimum Window

```java
int ans = Integer.MAX_VALUE;

while(condition){

    ans = Math.min(ans, right-left+1);

    left++;

}
```

---

# Frequency Window

```java
HashMap<Character,Integer> map = new HashMap<>();

for(char ch : s.toCharArray()){

    map.put(ch, map.getOrDefault(ch,0)+1);

}
```

---

# Interview Tip

Practice these templates until you can write them without referring to notes.