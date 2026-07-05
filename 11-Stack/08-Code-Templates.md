# ☕ Java Code Templates

---

# Basic Recursion

```java
void solve(int n){

    if(n == 0)
        return;

    solve(n - 1);

}
```

---

# Factorial

```java
int factorial(int n){

    if(n == 0)
        return 1;

    return n * factorial(n - 1);

}
```

---

# Fibonacci

```java
int fibonacci(int n){

    if(n <= 1)
        return n;

    return fibonacci(n - 1) + fibonacci(n - 2);

}
```

---

# Binary Search (Recursive)

```java
int binarySearch(int[] arr, int left, int right, int target){

    if(left > right)
        return -1;

    int mid = left + (right - left) / 2;

    if(arr[mid] == target)
        return mid;

    if(arr[mid] < target)
        return binarySearch(arr, mid + 1, right, target);

    return binarySearch(arr, left, mid - 1, target);

}
```

---

# Reverse String

```java
void reverse(char[] arr, int left, int right){

    if(left >= right)
        return;

    char temp = arr[left];
    arr[left] = arr[right];
    arr[right] = temp;

    reverse(arr, left + 1, right - 1);

}
```

---

# Interview Tip

Always write the **Base Case** before the recursive call.