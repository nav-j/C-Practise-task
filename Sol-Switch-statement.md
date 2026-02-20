Here is the **Answer Key** for all the switch tasks (without user input):

---

## ✅ Task 1 — Fixed Day Program

```c
#include <stdio.h>

int main() {
    int day = 5;

    switch(day) {
        case 1: printf("Monday"); break;
        case 2: printf("Tuesday"); break;
        case 3: printf("Wednesday"); break;
        case 4: printf("Thursday"); break;
        case 5: printf("Friday"); break;
        case 6: printf("Saturday"); break;
        case 7: printf("Sunday"); break;
        default: printf("Invalid day");
    }
    return 0;
}
```

---

## ✅ Task 2 — Fixed Calculator

```c
#include <stdio.h>

int main() {
    int a = 10, b = 5;
    char op = '*';

    switch(op) {
        case '+': printf("Result = %d", a + b); break;
        case '-': printf("Result = %d", a - b); break;
        case '*': printf("Result = %d", a * b); break;
        case '/': printf("Result = %d", a / b); break;
        default: printf("Invalid operator");
    }
    return 0;
}
```

---

## ✅ Task 3 — Fixed Character Check

```c
#include <stdio.h>

int main() {
    char ch = 'E';

    switch(ch) {
        case 'a': case 'e': case 'i': case 'o': case 'u':
        case 'A': case 'E': case 'I': case 'O': case 'U':
            printf("Vowel");
            break;
        default:
            printf("Consonant");
    }
    return 0;
}
```

---

## ✅ Task 4 — Grade Message

```c
#include <stdio.h>

int main() {
    char grade = 'B';

    switch(grade) {
        case 'A': printf("Excellent"); break;
        case 'B': printf("Very Good"); break;
        case 'C': printf("Good"); break;
        case 'D': printf("Pass"); break;
        case 'F': printf("Fail"); break;
        default: printf("Invalid Grade");
    }
    return 0;
}
```

---

## ✅ Task 5 — Menu Simulation

```c
#include <stdio.h>

int main() {
    int choice = 2;

    switch(choice) {
        case 1: printf("Hello"); break;
        case 2: printf("Welcome"); break;
        case 3: printf("Bye"); break;
        default: printf("Invalid choice");
    }
    return 0;
}
```

---

## ✅ Task 6 — Month Name

```c
#include <stdio.h>

int main() {
    int month = 8;

    switch(month) {
        case 1: printf("January"); break;
        case 2: printf("February"); break;
        case 3: printf("March"); break;
        case 4: printf("April"); break;
        case 5: printf("May"); break;
        case 6: printf("June"); break;
        case 7: printf("July"); break;
        case 8: printf("August"); break;
        case 9: printf("September"); break;
        case 10: printf("October"); break;
        case 11: printf("November"); break;
        case 12: printf("December"); break;
        default: printf("Invalid month");
    }
    return 0;
}
```

---

## ✅ Task 7 — Even/Odd Checker

```c
#include <stdio.h>

int main() {
    int num = 7;

    switch(num % 2) {
        case 0: printf("Even"); break;
        case 1: printf("Odd"); break;
    }
    return 0;
}
```

---

## ✅ Task 8 — Color Code

```c
#include <stdio.h>

int main() {
    char color = 'R';

    switch(color) {
        case 'R': printf("Red"); break;
        case 'G': printf("Green"); break;
        case 'B': printf("Blue"); break;
        default: printf("Invalid color");
    }
    return 0;
}
```

---

✅ **Tip for Exams:**
When the value is already declared, the program becomes a *trace-output* question — students must predict output instead of entering input.

---
