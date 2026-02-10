## **Task: Logical Operators in C**

For each program, **predict the output**.
Assume all variables are of type `int`.

> **Reminder:**
>
> * `0` → false
> * non-zero → true
> * Logical operators return `0` or `1`

---

### **Task 1: Logical AND (`&&`)**

```c
int main() {
    int a = 6;
    int b = 4;
    printf("%d", a > b && b > 0);
    return 0;
}
```

---

### **Task 2: Logical OR (`||`)**

```c
int main() {
    int x = 0;
    int y = 9;
    printf("%d", x || y < 5);
    return 0;
}
```

---

### **Task 3: Logical NOT (`!`)**

```c
int main() {
    int p = 7;
    printf("%d", !p);
    return 0;
}
```

---

### **Task 4: Combined Logical Operators**

```c
int main() {
    int x = 5;
    int y = 10;
    printf("%d", x < y && !(y == 10));
    return 0;
}
```

---

### **Task 5: Logical AND with Arithmetic**

```c
int main() {
    int a = 12;
    int b = 3;
    printf("%d", a / b == 4 && a % b == 0);
    return 0;
}
```

---

### **Task 6: Logical OR with NOT**

```c
int main() {
    int m = 0;
    int n = 6;
    printf("%d", !m || n == 0);
    return 0;
}
```

---

### **Task 7: Multiple Logical Conditions**

```c
int main() {
    int x = 8;
    int y = 2;
    printf("%d", x > 5 && y < 3 && x % y == 0);
    return 0;
}
```
