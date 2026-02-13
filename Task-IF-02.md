Here is one more **`if` statement task (without user input)** 👇

---

## 📝 Task: Check Whether a Person is Eligible to Vote

### 🎯 Problem Statement:

Write a C program that:

1. Declares an integer variable `age` and assigns it a value.
2. Uses an `if` statement to check whether the person is **18 or older**.
3. If the condition is true, print:
   `"You are eligible to vote."`

---

### 💻 Example:

If `age = 20`, the output should be:

```
You are eligible to vote.
```

---

### 📌 Starter Code (Students Complete It)

```c
#include <stdio.h>

int main() {
    int age = 20;

    // Write your if condition here

    return 0;
}
```

---
Here is the ✅ **Answer Key** for the task:

---

## 📝 Task: Check Whether a Person is Eligible to Vote

### ✔ Complete Program:

```c
#include <stdio.h>

int main() {
    int age = 20;

    if (age >= 18) {
        printf("You are eligible to vote.");
    }

    return 0;
}
```

---

### 📌 Explanation:

* The condition `age >= 18` checks whether the person is **18 or older**.
* Since `age = 20`, the condition is **true**.
* Therefore, the program prints:

```
You are eligible to vote.
```

---

If you want, I can now create:

* 🔹 Version using `if-else`
* 🔹 Nested `if` task
* 🔹 Full practice sheet for your students
