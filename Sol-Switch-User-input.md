Here is the **Answer Key** for all the `switch` statement tasks:

---

## ✅ Task 1 — Day of Week

```c
#include <stdio.h>

int main() {
    int day;
    printf("Enter number (1-7): ");
    scanf("%d", &day);

    switch(day) {
        case 1: printf("Monday"); break;
        case 2: printf("Tuesday"); break;
        case 3: printf("Wednesday"); break;
        case 4: printf("Thursday"); break;
        case 5: printf("Friday"); break;
        case 6: printf("Saturday"); break;
        case 7: printf("Sunday"); break;
        default: printf("Invalid input");
    }
    return 0;
}
```

---

## ✅ Task 2 — Simple Calculator

```c
#include <stdio.h>

int main() {
    int a, b;
    char op;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    printf("Enter operator (+,-,*,/): ");
    scanf(" %c", &op);

    switch(op) {
        case '+': printf("Result = %d", a + b); break;
        case '-': printf("Result = %d", a - b); break;
        case '*': printf("Result = %d", a * b); break;
        case '/': 
            if(b != 0)
                printf("Result = %d", a / b);
            else
                printf("Division by zero not allowed");
            break;
        default: printf("Invalid operator");
    }
    return 0;
}
```

---

## ✅ Task 3 — Vowel or Consonant

```c
#include <stdio.h>

int main() {
    char ch;
    printf("Enter a character: ");
    scanf(" %c", &ch);

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

## ✅ Task 4 — Grade System

```c
#include <stdio.h>

int main() {
    char grade;
    printf("Enter grade: ");
    scanf(" %c", &grade);

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

## ✅ Task 5 — Menu Driven Program

```c
#include <stdio.h>

int main() {
    int choice, a, b;

    printf("1. Addition\n2. Subtraction\n3. Exit\n");
    printf("Enter choice: ");
    scanf("%d", &choice);

    switch(choice) {
        case 1:
            printf("Enter two numbers: ");
            scanf("%d %d", &a, &b);
            printf("Sum = %d", a + b);
            break;

        case 2:
            printf("Enter two numbers: ");
            scanf("%d %d", &a, &b);
            printf("Difference = %d", a - b);
            break;

        case 3:
            printf("Exiting...");
            break;

        default:
            printf("Invalid choice");
    }
    return 0;
}
```

---

✅ **Tip for Students:**
Always include `break;` inside each `case` unless you intentionally want fall-through behavior.

---
