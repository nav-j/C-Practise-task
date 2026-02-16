 **Nested `if` practice tasks in C (without user input)** 

---

#  Task 1: Eligible for Scholarship

###  Problem:

Declare:

```c
int marks = 85;
int income = 200000;
```

Conditions:

* If marks are **80 or above**

  * Then check if income is **less than 300000**

    * Print `"Eligible for Scholarship"`
    * Otherwise print `"Not Eligible (Income High)"`
* Otherwise print `"Not Eligible (Low Marks)"`

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int marks = 85;
    int income = 200000;

    // Write nested if here

    return 0;
}
```

---

# Task 2: Find Largest of Three Numbers (Using Nested if)

###  Problem:

Declare:

```c
int a = 10, b = 20, c = 15;
```

Use nested `if` to find the largest number.

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int a = 10, b = 20, c = 15;

    // Write nested if here

    return 0;
}
```

---

#  Task 3: Login System

###  Problem:

Declare:

```c
int password = 1234;
int otp = 5678;
```

Conditions:

* If password is correct (1234)

  * Then check if OTP is correct (5678)

    * Print `"Login Successful"`
    * Otherwise print `"Wrong OTP"`
* Otherwise print `"Wrong Password"`

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int password = 1234;
    int otp = 5678;

    // Write nested if here

    return 0;
}
```

---

#  Task 4: Check Positive Even Number

###  Problem:

Declare:

```c
int num = 8;
```

Conditions:

* If number is positive

  * Then check if number is even

    * Print `"Positive Even Number"`
    * Otherwise print `"Positive Odd Number"`
* Otherwise print `"Negative Number"`

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int num = 8;

    // Write nested if here

    return 0;
}
```

---
Here is the ✅ **Answer Key for all Nested `if` Tasks**

---

# ✔ Task 1: Eligible for Scholarship

```c
#include <stdio.h>

int main() {
    int marks = 85;
    int income = 200000;

    if (marks >= 80) {
        if (income < 300000) {
            printf("Eligible for Scholarship");
        } else {
            printf("Not Eligible (Income High)");
        }
    } else {
        printf("Not Eligible (Low Marks)");
    }

    return 0;
}
```

 Since marks = 85 and income = 200000, output:

```
Eligible for Scholarship
```

---

# ✔ Task 2: Largest of Three Numbers (Nested if)

```c
#include <stdio.h>

int main() {
    int a = 10, b = 20, c = 15;

    if (a > b) {
        if (a > c) {
            printf("Largest number is %d", a);
        } else {
            printf("Largest number is %d", c);
        }
    } else {
        if (b > c) {
            printf("Largest number is %d", b);
        } else {
            printf("Largest number is %d", c);
        }
    }

    return 0;
}
```
Since 20 is largest, output:

```
Largest number is 20
```

---

# ✔ Task 3: Login System

```c
#include <stdio.h>

int main() {
    int password = 1234;
    int otp = 5678;

    if (password == 1234) {
        if (otp == 5678) {
            printf("Login Successful");
        } else {
            printf("Wrong OTP");
        }
    } else {
        printf("Wrong Password");
    }

    return 0;
}
```
 Since both password and OTP are correct, output:

```
Login Successful
```

---

# ✔ Task 4: Check Positive Even Number

```c
#include <stdio.h>

int main() {
    int num = 8;

    if (num > 0) {
        if (num % 2 == 0) {
            printf("Positive Even Number");
        } else {
            printf("Positive Odd Number");
        }
    } else {
        printf("Negative Number");
    }

    return 0;
}
```

 Since 8 is positive and even, output:

```
Positive Even Number
```
