Here’s the **answer key** with clear, step-by-step explanations 👇

---

## ✅ **Answer Key: Logical Operators in C**

> Reminder:
> `0 = false`, `1 = true`

---

### **Task 1: Logical AND (`&&`)**

```c
int a = 6;
int b = 4;
a > b && b > 0
```

* `6 > 4` → true (1)
* `4 > 0` → true (1)
* `1 && 1` → **1**

✅ **Output:**

```
1
```

---

### **Task 2: Logical OR (`||`)**

```c
int x = 0;
int y = 9;
x || y < 5
```

* `y < 5` → `9 < 5` → false (0)
* `0 || 0` → **0**

✅ **Output:**

```
0
```

---

### **Task 3: Logical NOT (`!`)**

```c
int p = 7;
!p
```

* `p` is non-zero → true
* `!true` → **false (0)**

✅ **Output:**

```
0
```

---

### **Task 4: Combined Logical Operators**

```c
int x = 5;
int y = 10;
x < y && !(y == 10)
```

* `5 < 10` → true (1)
* `y == 10` → true (1)
* `!(1)` → 0
* `1 && 0` → **0**

✅ **Output:**

```
0
```

---

### **Task 5: Logical AND with Arithmetic**

```c
int a = 12;
int b = 3;
a / b == 4 && a % b == 0
```

* `12 / 3 = 4` → true
* `12 % 3 = 0` → true
* `1 && 1` → **1**

✅ **Output:**

```
1
```

---

### **Task 6: Logical OR with NOT**

```c
int m = 0;
int n = 6;
!m || n == 0
```

* `!0` → true (1)
* `6 == 0` → false (0)
* `1 || 0` → **1**

✅ **Output:**

```
1
```

---

### **Task 7: Multiple Logical Conditions**

```c
int x = 8;
int y = 2;
x > 5 && y < 3 && x % y == 0
```

* `8 > 5` → true
* `2 < 3` → true
* `8 % 2 = 0` → true
* `1 && 1 && 1` → **1**

✅ **Output:**

```
1
```

---

## 📊 **Final Output Summary**

| Task   | Output |
| ------ | ------ |
| Task 1 | 1      |
| Task 2 | 0      |
| Task 3 | 0      |
| Task 4 | 0      |
| Task 5 | 1      |
| Task 6 | 1      |
| Task 7 | 1      |

---

If you want next:

* 🧠 **Tricky logical-operator questions**
* 📝 **MCQs with explanations**
* 📘 **Complete C operators revision worksheet**

Just tell me 😊
