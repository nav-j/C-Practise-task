Here is the **Answer Key** for all the `switch` practice tasks.

---

# ✅ Switch Case Tasks — Answer Key (C Programs)

---

## ✔ Task 1 — Day of Week

```c
#include <stdio.h>

int main() {
    int day = 3;

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

## ✔ Task 2 — Simple Calculator

```c
#include <stdio.h>

int main() {
    int a = 10, b = 5;
    char op = '+';

    switch(op) {
        case '+': printf("Sum = %d", a + b); break;
        case '-': printf("Difference = %d", a - b); break;
        case '*': printf("Product = %d", a * b); break;
        case '/': printf("Quotient = %d", a / b); break;
        default: printf("Invalid operator");
    }
    return 0;
}
```

---

## ✔ Task 3 — Vowel Checker

```c
#include <stdio.h>

int main() {
    char ch = 'e';

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

## ✔ Task 4 — Menu Driven Program

```c
#include <stdio.h>

int main() {
    int choice = 2;

    switch(choice) {
        case 1:
            printf("Area of Square = %d", 4 * 4);
            break;

        case 2:
            printf("Area of Circle = %.2f", 3.14 * 3 * 3);
            break;

        case 3:
            printf("Area of Rectangle = %d", 5 * 2);
            break;

        default:
            printf("Invalid choice");
    }
    return 0;
}
```

---

## ✔ Task 5 — Grade Message

```c
#include <stdio.h>

int main() {
    char grade = 'B';

    switch(grade) {
        case 'A': printf("Excellent"); break;
        case 'B': printf("Good"); break;
        case 'C': printf("Average"); break;
        case 'D': printf("Needs Improvement"); break;
        case 'F': printf("Fail"); break;
        default: printf("Invalid grade");
    }
    return 0;
}
```

---

## ⭐ Bonus — Nested Switch Program

```c
#include <stdio.h>

int main() {
    int lang = 1;
    int greet = 2;

    switch(lang) {
        case 1:
            switch(greet) {
                case 1: printf("Hello"); break;
                case 2: printf("Welcome"); break;
                default: printf("Invalid greeting");
            }
            break;

        case 2:
            switch(greet) {
                case 1: printf("Namaste"); break;
                case 2: printf("Swagat Hai"); break;
                default: printf("Invalid greeting");
            }
            break;

        default:
            printf("Invalid language");
    }
    return 0;
}
```

---

✅ **Tip for Students:**
Always remember to use `break;` in each case — otherwise execution will continue to the next case (called *fall-through*).

---
