Here is a **C task using `if` statement (without user input)** 👇

---

## 📝 Task: Check Whether a Number is Even or Odd

### 🎯 Problem Statement:

Write a C program that:

1. Declares an integer variable and assigns it a value.
2. Uses an `if` statement to check whether the number is **even**.
3. If the number is even, print:
   `"The number is even."`

---

### 💻 Example:

If the number is `10`, the output should be:

```
The number is even.
```

---

### 📌 Starter Code (Students Complete It)

```c
#include <stdio.h>

int main() {
    int num = 10;

    // Write your if condition here

    return 0;
}
```

---


Here is the ✅ **Answer Key** for the task:

---

## 📝 Task: Check Whether a Number is Even or Odd (Without Input)

### ✔ Complete Program:

```c
#include <stdio.h>

int main() {
    int num = 10;

    if (num % 2 == 0) {
        printf("The number is even.");
    }

    return 0;
}
```

---

### 📌 Explanation:

* `num % 2` gives the remainder when divided by 2.
* If the remainder is `0`, the number is **even**.
* Since `10 % 2 == 0`, the condition is **true**, so it prints:

```
The number is even.
```

---

If you want, I can also provide:

* 🔹 Version with `if-else`
* 🔹 Practice sheet with multiple `if` questions
* 🔹 Test paper format for your students 😊

