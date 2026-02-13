Here is a **Short Test Paper on `if`, `if-else`, and Nested `if` in C Programming** 👇

---

# 📝 C Programming Test

## 📘 Topic: Decision Making Statements (`if`, `if-else`, `if-else if`, Nested `if`)

**Time: 45 Minutes**
**Total Marks: 30**

---

# ✅ Section A – Very Short Answer (1 × 5 = 5 Marks)

*(Answer in 1–2 lines)*

1. What is the purpose of the `if` statement in C?
2. Write the syntax of `if-else` statement.
3. What is a nested `if` statement?
4. Which operator is used to check equality in C?
5. What will be the output?

```c
int x = 5;
if (x > 3)
    printf("Hello");
```

---

# ✅ Section B – Short Answer / Programs (5 × 3 = 15 Marks)

### 1. Write a program to check whether a number is positive or negative.

(Declare variable inside program, no input required)

---

### 2. Write a program to check whether a number is even or odd using `if-else`.

---

### 3. Write a program to print grade according to marks:

* 90 and above → Grade A
* 75–89 → Grade B
* Below 75 → Grade C

---

### 4. Write a program to find the greater number between two numbers.

---

### 5. Write a program using nested `if` to check:

If a number is positive, then check whether it is even or odd.

---

# ✅ Section C – Long Answer (5 × 2 = 10 Marks)

### 1. Write a program to find the largest of three numbers using nested `if`.

---

### 2. Write a program for a login system:

* If password is correct
* Then check OTP
* Print appropriate message

---
Here is the ✅ **Complete Answer Key** for the Test Paper

---

# ✅ Section A – Very Short Answers

**1.** The `if` statement is used to execute a block of code only when a condition is true.

**2. Syntax of `if-else`:**

```c
if (condition) {
    // code
} else {
    // code
}
```

**3.** A nested `if` statement is an `if` statement inside another `if` statement.

**4.** The equality operator in C is: `==`

**5. Output:**

```
Hello
```

(Because 5 > 3 is true.)

---

# ✅ Section B – Short Programs

---

## ✔ 1. Positive or Negative

```c
#include <stdio.h>

int main() {
    int num = -4;

    if (num >= 0)
        printf("Positive");
    else
        printf("Negative");

    return 0;
}
```

---

## ✔ 2. Even or Odd

```c
#include <stdio.h>

int main() {
    int num = 7;

    if (num % 2 == 0)
        printf("Even");
    else
        printf("Odd");

    return 0;
}
```

---

## ✔ 3. Grade Program

```c
#include <stdio.h>

int main() {
    int marks = 85;

    if (marks >= 90)
        printf("Grade A");
    else if (marks >= 75)
        printf("Grade B");
    else
        printf("Grade C");

    return 0;
}
```

---

## ✔ 4. Greater Between Two Numbers

```c
#include <stdio.h>

int main() {
    int a = 10, b = 20;

    if (a > b)
        printf("Greater number is %d", a);
    else
        printf("Greater number is %d", b);

    return 0;
}
```

---

## ✔ 5. Nested `if` (Positive Even or Odd)

```c
#include <stdio.h>

int main() {
    int num = 8;

    if (num > 0) {
        if (num % 2 == 0)
            printf("Positive Even");
        else
            printf("Positive Odd");
    } else {
        printf("Negative Number");
    }

    return 0;
}
```

---

# ✅ Section C – Long Programs

---

## ✔ 1. Largest of Three Numbers (Nested `if`)

```c
#include <stdio.h>

int main() {
    int a = 10, b = 25, c = 15;

    if (a > b) {
        if (a > c)
            printf("Largest is %d", a);
        else
            printf("Largest is %d", c);
    } else {
        if (b > c)
            printf("Largest is %d", b);
        else
            printf("Largest is %d", c);
    }

    return 0;
}
```

---

## ✔ 2. Login System

```c
#include <stdio.h>

int main() {
    int password = 1234;
    int otp = 5678;

    if (password == 1234) {
        if (otp == 5678)
            printf("Login Successful");
        else
            printf("Wrong OTP");
    } else {
        printf("Wrong Password");
    }

    return 0;
}
```

---

If you want, I can now:

* 📄 Format this as a printable PDF-style paper
* 📝 Create a more difficult version (logic-based problems)
* 📊 Create a marking scheme with step-wise marks 😊
