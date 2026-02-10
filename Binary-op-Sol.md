## **Answer Key: Bitwise Operators Task**

---

### **Task 1: XOR Assignment**

```c
int x = 12;
x ^= 5;
```

Binary:

```
12 = 1100
5  = 0101
-----------
XOR=1001
```

Decimal:

```
1001 = 9
```
 **Output:**

```
9
```

---

### **Task 2: Right Shift Assignment**

```c
int x = 20;
x >>= 2;
```

Binary:

```
20 = 10100
```

Right shift by 2:

```
10100 → 00101
```

Decimal:

```
00101 = 5
```

(Or: `20 ÷ 2² = 20 ÷ 4 = 5`)

 **Output:**

```
5
```

---

### **Task 3: Left Shift Assignment**

```c
int x = 7;
x <<= 4;
```

Binary:

```
7 = 0111
```

Left shift by 4:

```
0111 → 01110000
```

Decimal:

```
7 × 2⁴ = 7 × 16 = 112
```

 **Output:**

```
112
```

---

### **Task 4: Combined Operations**

```c
int x = 10;
x <<= 1;
x ^= 3;
```

Step 1 – Left shift:

```
10 << 1 = 20
```

Binary:

```
20 = 10100
3  = 00011
-----------
XOR=10111
```

Decimal:

```
10111 = 23
```

 **Output:**

```
23
```

---

### **Task 5: Predict the Output**

```c
int x = 18;
x >>= 3;
x <<= 2;
```

Step 1 – Right shift:

```
18 ÷ 2³ = 18 ÷ 8 = 2
```

Step 2 – Left shift:

```
2 × 2² = 2 × 4 = 8
```

 **Output:**

```
8
```

---

##  **Quick Summary Table**

| Task   | Final Output |
| ------ | ------------ |
| Task 1 | 9            |
| Task 2 | 5            |
| Task 3 | 112          |
| Task 4 | 23           |
| Task 5 | 8            |
