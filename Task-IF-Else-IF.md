**`if-else if` practice tasks in C (without user input)** 

---

# Task 1: Grade Calculator

###  Problem:

Declare `int marks = 75;`

Use `if-else if` to print grade according to marks:

* 90 and above → `"Grade A"`
* 75 to 89 → `"Grade B"`
* 50 to 74 → `"Grade C"`
* Below 50 → `"Fail"`

### Starter Code:

```c
#include <stdio.h>

int main() {
    int marks = 75;

    // Write your if-else if condition here

    return 0;
}
```

---

# Task 2: Largest of Three Numbers

###  Problem:

Declare three integers:
`int a = 10, b = 25, c = 15;`

Use `if-else if` to print the largest number.

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int a = 10, b = 25, c = 15;

    // Write your if-else if condition here

    return 0;
}
```

---

#  Task 3: Number Type Checker

###  Problem:

Declare `int num = 0;`

Use `if-else if` to check:

* If number is positive
* If number is negative
* Otherwise print `"Number is Zero"`

### Starter Code:

```c
#include <stdio.h>

int main() {
    int num = 0;

    // Write your if-else if condition here

    return 0;
}
```

---

#  Task 4: Weekday Checker

###  Problem:

Declare `int day = 3;`

Use `if-else if` to print:
1 → Monday
2 → Tuesday
3 → Wednesday
4 → Thursday
5 → Friday
Otherwise → `"Invalid day"`

###  Starter Code:

```c
#include <stdio.h>

int main() {
    int day = 3;

    // Write your if-else if condition here

    return 0;
}
```

---

Here is the ✅ **Answer Key for all `if-else if` practice tasks**

---

# ✔ Task 1: Grade Calculator

```c
#include <stdio.h>

int main() {
    int marks = 75;

    if (marks >= 90) {
        printf("Grade A");
    } else if (marks >= 75) {
        printf("Grade B");
    } else if (marks >= 50) {
        printf("Grade C");
    } else {
        printf("Fail");
    }

    return 0;
}
```

 Since `marks = 75`, output:

```
Grade B
```

---

# ✔ Task 2: Largest of Three Numbers

```c
#include <stdio.h>

int main() {
    int a = 10, b = 25, c = 15;

    if (a >= b && a >= c) {
        printf("Largest number is %d", a);
    } else if (b >= a && b >= c) {
        printf("Largest number is %d", b);
    } else {
        printf("Largest number is %d", c);
    }

    return 0;
}
```

 Since `b = 25` is largest, output:

```
Largest number is 25
```

---

# ✔ Task 3: Number Type Checker

```c
#include <stdio.h>

int main() {
    int num = 0;

    if (num > 0) {
        printf("Number is positive");
    } else if (num < 0) {
        printf("Number is negative");
    } else {
        printf("Number is Zero");
    }

    return 0;
}
```

Since `num = 0`, output:

```
Number is Zero
```

---

# ✔ Task 4: Weekday Checker

```c
#include <stdio.h>

int main() {
    int day = 3;

    if (day == 1) {
        printf("Monday");
    } else if (day == 2) {
        printf("Tuesday");
    } else if (day == 3) {
        printf("Wednesday");
    } else if (day == 4) {
        printf("Thursday");
    } else if (day == 5) {
        printf("Friday");
    } else {
        printf("Invalid day");
    }

    return 0;
}
```

 Since `day = 3`, output:

```
Wednesday
```
