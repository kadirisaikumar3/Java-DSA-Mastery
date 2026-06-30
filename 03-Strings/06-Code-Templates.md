# ☕ Java Code Templates

---

# Traverse String

```java
for(int i = 0; i < str.length(); i++){

    System.out.print(str.charAt(i));

}
```

---

# Reverse String

```java
StringBuilder sb = new StringBuilder(str);

System.out.println(sb.reverse());
```

---

# Convert to Character Array

```java
char[] arr = str.toCharArray();
```

---

# Character Frequency

```java
int[] freq = new int[26];

for(char ch : str.toCharArray()){

    freq[ch-'a']++;

}
```

---

# Compare Strings

```java
str1.equals(str2)
```

---

# Ignore Case

```java
str1.equalsIgnoreCase(str2)
```

---

# Check Palindrome

```java
int left = 0;
int right = str.length()-1;

while(left < right){

    if(str.charAt(left) != str.charAt(right))
        return false;

    left++;
    right--;
}

return true;
```

---

# Interview Tip

Master Java String methods before interviews:

- length()
- charAt()
- substring()
- equals()
- compareTo()
- contains()
- replace()
- split()
- trim()