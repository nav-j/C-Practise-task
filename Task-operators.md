Nice 👍 Here’s a **practice task set using mixed operators in C** (arithmetic + comparison + logical + assignment), perfect for strengthening fundamentals.

---

## 📝 **Task: Mixed Operators in C**

For each program, **predict the final output**.
Assume all variables are of type `int`.

---

### **Task 1: Arithmetic + Comparison**

```c
int main() {
    int a = 10;
    int b = 3;
    printf("%d", a / b > 2);
    return 0;
}
```

---

### **Task 2: Assignment + Arithmetic**

```c
int main() {
    int x = 5;
    x += 4 * 2;
    printf("%d", x);
    return 0;
}
```

---

### **Task 3: Arithmetic + Logical AND**

```c
int main() {
    int p = 12;
    int q = 4;
    printf("%d", p / q == 3 && p % q == 0);
    return 0;
}
```

---

### **Task 4: Comparison + Logical OR**

```c
int main() {
    int x = 0;
    int y = 7;
    printf("%d", x > 0 || y < 10);
    return 0;
}
```

---

### **Task 5: Assignment + Logical + Comparison**

```c
int main() {
    int a = 6;
    int b = 2;
    a *= b + 1;
    printf("%d", a > 15 && b < 3);
    return 0;
}
```

---

### **Task 6: Bitwise + Arithmetic**

```c
int main() {
    int x = 5;
    x <<= 2;
    printf("%d", x + 3);
    return 0;
}
```

---

### **Task 7: Logical NOT + Comparison**

```c
int main() {
    int x = 4;
    printf("%d", !(x == 5) && x > 2);
    return 0;
}
```

---

### **Task 8: Mixed Assignment Chain**

```c
int main() {
    int x = 10;
    x -= 3;
    x /= 7;
    printf("%d", x == 1);
    return 0;
}
```

---

## 🎯 **Instructions**

* Follow operator precedence:
  `()` → `!` → `*, /, %` → `+, -` → comparison → `&&` → `||`
* Integer division discards decimals
* Final output is **0 or 1** unless printing a number

If you want, I can:

* ✅ Provide the **answer key**
* 🧠 Increase difficulty (tricky exam-level)
* 📄 Convert into a **worksheet / MCQs**

Just say 😊
