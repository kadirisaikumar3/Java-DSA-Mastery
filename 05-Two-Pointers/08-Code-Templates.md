# ☕ Java Code Templates

---

# Opposite Direction Template

```java
int left = 0;
int right = arr.length - 1;

while(left < right){

    if(condition){

        left++;

    }else{

        right--;

    }

}
```

---

# Same Direction Template

```java
int slow = 0;

for(int fast = 0; fast < arr.length; fast++){

    if(condition){

        arr[slow] = arr[fast];

        slow++;

    }

}
```

---

# Fast & Slow Pointer Template

```java
ListNode slow = head;
ListNode fast = head;

while(fast != null && fast.next != null){

    slow = slow.next;

    fast = fast.next.next;

}
```

---

# Reverse String

```java
int left = 0;
int right = s.length() - 1;

while(left < right){

    char temp = s[left];
    s[left] = s[right];
    s[right] = temp;

    left++;
    right--;

}
```

---

# Remove Duplicates

```java
int slow = 0;

for(int fast = 1; fast < nums.length; fast++){

    if(nums[fast] != nums[slow]){

        slow++;

        nums[slow] = nums[fast];

    }

}

return slow + 1;
```

---

# Interview Tip

Memorize these templates—they solve a large number of Two Pointer problems.