 **practice tasks using `if-else` in C (without user input)**

---

#  Task 1: Check Positive or Negative

###  Problem:

Declare an integer variable `num = -5`.
Use `if-else` to check whether the number is **positive or negative**.

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int num = -5;

    // Write your if-else condition here

    return 0;
}
```

---

#  Task 2: Check Even or Odd

###  Problem:

Declare `int num = 7;`
Use `if-else` to check whether the number is **even or odd**.

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int num = 7;

    // Write your if-else condition here

    return 0;
}
```

---

#  Task 3: Check Pass or Fail

###  Problem:

Declare `int marks = 35;`
If marks are **40 or above**, print `"Pass"`.
Otherwise, print `"Fail"`.

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int marks = 35;

    // Write your if-else condition here

    return 0;
}
```

---

#  Task 4: Check Greater Number

###  Problem:

Declare two integers:
`int a = 15, b = 20;`
Use `if-else` to print the greater number.

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int a = 15, b = 20;

    // Write your if-else condition here

    return 0;
}
```

---
Here is the ✅ **Answer Key for all `if-else` tasks**

---

# ✔ Task 1: Check Positive or Negative

```c
#include <stdio.h>

int main() {
    int num = -5;

    if (num >= 0) {
        printf("The number is positive.");
    } else {
        printf("The number is negative.");
    }

    return 0;
}
```

Since `num = -5`, output will be:

```
The number is negative.
```

---

# ✔ Task 2: Check Even or Odd

```c
#include <stdio.h>

int main() {
    int num = 7;

    if (num % 2 == 0) {
        printf("The number is even.");
    } else {
        printf("The number is odd.");
    }

    return 0;
}
```

 Since `7 % 2 != 0`, output:

```
The number is odd.
```

---

# ✔ Task 3: Check Pass or Fail

```c
#include <stdio.h>

int main() {
    int marks = 35;

    if (marks >= 40) {
        printf("Pass");
    } else {
        printf("Fail");
    }

    return 0;
}
```

 Since `35 < 40`, output:

```
Fail
```

---

# ✔ Task 4: Check Greater Number

```c
#include <stdio.h>

int main() {
    int a = 15, b = 20;

    if (a > b) {
        printf("Greater number is %d", a);
    } else {
        printf("Greater number is %d", b);
    }

    return 0;
}
```

 Since `20 > 15`, output:

```
Greater number is 20
```
