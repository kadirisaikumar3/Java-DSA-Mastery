# ☕ Java Code Templates

---

# Array Traversal

```java
for(int i=0;i<arr.length;i++){

    System.out.print(arr[i]+" ");

}
```

---

# Enhanced For Loop

```java
for(int num : arr){

    System.out.println(num);

}
```

---

# Find Maximum

```java
int max = arr[0];

for(int num : arr){

    if(num > max)

        max = num;

}
```

---

# Find Minimum

```java
int min = arr[0];

for(int num : arr){

    if(num < min)

        min = num;

}
```

---

# Reverse Array

```java
int left=0;

int right=arr.length-1;

while(left<right){

    int temp=arr[left];

    arr[left]=arr[right];

    arr[right]=temp;

    left++;

    right--;

}
```

---

# Linear Search

```java
for(int i=0;i<arr.length;i++){

    if(arr[i]==target)

        return i;

}

return -1;
```

---

# Sum of Array

```java
int sum=0;

for(int num : arr){

    sum += num;

}
```

---

# Interview Tip

Practice writing these templates without looking.

Speed matters in coding interviews.