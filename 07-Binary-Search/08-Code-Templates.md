# ☕ Java Code Templates

---

# Classic Binary Search

```java
int left = 0;
int right = arr.length - 1;

while(left <= right){

    int mid = left + (right - left) / 2;

    if(arr[mid] == target)
        return mid;

    if(arr[mid] < target)
        left = mid + 1;
    else
        right = mid - 1;

}

return -1;
```

---

# Lower Bound

```java
int ans = arr.length;

while(left <= right){

    int mid = left + (right-left)/2;

    if(arr[mid] >= target){

        ans = mid;
        right = mid - 1;

    }else{

        left = mid + 1;

    }

}
```

---

# Upper Bound

```java
int ans = arr.length;

while(left <= right){

    int mid = left + (right-left)/2;

    if(arr[mid] > target){

        ans = mid;
        right = mid - 1;

    }else{

        left = mid + 1;

    }

}
```

---

# Search on Answer

```java
while(left < right){

    int mid = left + (right-left)/2;

    if(isPossible(mid))

        right = mid;

    else

        left = mid + 1;

}
```

---

# Overflow Safe Mid

```java
int mid = left + (right-left)/2;
```

---

# Interview Tip

Never calculate:

```java
(left + right) / 2
```

It may overflow for very large values.