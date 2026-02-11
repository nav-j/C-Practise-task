##  **Answer Key: Arithmetic Operators in C**

---

### **Task 1: Addition & Subtraction**

```c
int a = 18;
int b = 7;
int c = a - b + 5;
```

Calculation:

```
18 - 7 = 11
11 + 5 = 16
```
 **Output:**

```
16
```

---

### **Task 2: Multiplication & Division**

```c
int x = 24;
int y = 5;
int z = x * y / 10;
```

Calculation:

```
24 × 5 = 120
120 ÷ 10 = 12
```
 **Output:**

```
12
```

---

### **Task 3: Modulus Operator**

```c
int p = 35;
int q = 8;
p % q
```

Calculation:

```
35 ÷ 8 = 4 remainder 3
```

 **Output:**

```
3
```

---

### **Task 4: Mixed Arithmetic Operators**

```c
int a = 10;
int b = 4;
int c = a + b * 3 - a / b;
```

Operator precedence:

```
b * 3 = 12
a / b = 10 / 4 = 2   (integer division)
```

Final:

```
10 + 12 - 2 = 20
```

 **Output:**

```
20
```

---

### **Task 5: Increment Operator**

```c
int x = 6;
x++;        // x = 7
x = x * 3;  // x = 21
```

 **Output:**

```
21
```

---

### **Task 6: Decrement Operator**

```c
int y = 20;
y--;        // y = 19
y = y / 3;  // 19 / 3 = 6
```

 **Output:**

```
6
```

---

### **Task 7: Operator Precedence**

```c
int a = 8;
int b = 2;
int c = a * b + a / b - b;
```

Step-by-step:

```
a * b = 16
a / b = 4
```

Final:

```
16 + 4 - 2 = 18
```

 **Output:**

```
18
```

---

##  **Final Output Summary**

| Task   | Output |
| ------ | ------ |
| Task 1 | 16     |
| Task 2 | 12     |
| Task 3 | 3      |
| Task 4 | 20     |
| Task 5 | 21     |
| Task 6 | 6      |
| Task 7 | 18     |
