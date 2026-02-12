## **Answer Key: Mixed Operators in C**

---

### **Task 1: Arithmetic + Comparison**

```c
int a = 10;
int b = 3;
a / b > 2
```

* `10 / 3 = 3` (integer division)
* `3 > 2` → **true**

 **Output:**

```
1
```

---

### **Task 2: Assignment + Arithmetic**

```c
int x = 5;
x += 4 * 2;
```

* `4 * 2 = 8`
* `x = 5 + 8 = 13`

 **Output:**

```
13
```

---

### **Task 3: Arithmetic + Logical AND**

```c
int p = 12;
int q = 4;
p / q == 3 && p % q == 0
```

* `12 / 4 = 3` → true
* `12 % 4 = 0` → true
* `true && true` → **true**

 **Output:**

```
1
```

---

### **Task 4: Comparison + Logical OR**

```c
int x = 0;
int y = 7;
x > 0 || y < 10
```

* `x > 0` → false
* `y < 10` → true
* `false || true` → **true**

 **Output:**

```
1
```

---

### **Task 5: Assignment + Logical + Comparison**

```c
int a = 6;
int b = 2;
a *= b + 1;
```

* `b + 1 = 3`
* `a = 6 × 3 = 18`

Now check:

```c
a > 15 && b < 3
```

* `18 > 15` → true
* `2 < 3` → true
* `true && true` → **true**

 **Output:**

```
1
```

---

### **Task 6: Bitwise + Arithmetic**

```c
int x = 5;
x <<= 2;
x + 3
```

* `5 << 2 = 20`
* `20 + 3 = 23`

 **Output:**

```
23
```

---

### **Task 7: Logical NOT + Comparison**

```c
int x = 4;
!(x == 5) && x > 2
```

* `x == 5` → false
* `!(false)` → true
* `x > 2` → true
* `true && true` → **true**

 **Output:**

```
1
```

---

### **Task 8: Mixed Assignment Chain**

```c
int x = 10;
x -= 3;   // x = 7
x /= 7;   // x = 1
x == 1
```

* Condition is true

 **Output:**

```
1
```

---

##  **Final Output Summary**

| Task   | Output |
| ------ | ------ |
| Task 1 | 1      |
| Task 2 | 13     |
| Task 3 | 1      |
| Task 4 | 1      |
| Task 5 | 1      |
| Task 6 | 23     |
| Task 7 | 1      |
| Task 8 | 1      |
