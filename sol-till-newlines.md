
## **Answer Key**

---

## **Section A: Short Answer Questions**

1. **Purpose of `#include <stdio.h>`**
   It allows the use of standard input and output functions such as `printf()` and `scanf()`.

2. **Function of `printf()`**
   It is used to display output on the screen.

3. **Syntax of `main()` function**

   ```c
   int main() {
       // statements
       return 0;
   }
   ```

4. **Role of `return 0;`**
   It terminates the `main()` function and returns control to the operating system, indicating successful execution.

5. **Does C ignore white spaces?**
   Yes, C ignores extra white spaces such as blank lines, tabs, and spaces.

6. **Purpose of `main()` function**
   It is the entry point of a C program where execution begins.

7. **Use of semicolon (`;`)**
   It marks the end of a statement in C.

8. **Output of `printf("Hello World!");`**

   ```
   Hello World!
   ```

9. **Function used to print output in C**
   `printf()`

10. **Meaning of `\n`**
    It represents a new line.

11. **Multiple `printf()` usage**
    Yes, we can use more than one `printf()` function in a program.

12. **Execution of statements in C**
    Statements are executed one by one in the order they are written.

---

## **Section B: Long Answer Questions**

### **1. Purpose of `#include <stdio.h>` and `printf()`**

`#include <stdio.h>` includes the Standard Input Output header file, which allows the use of functions like `printf()`.

`printf()` is used to display output on the screen.

**Example:**

```c
#include <stdio.h>

int main() {
    printf("Hello World!");
    return 0;
}
```

---

### **2. Structure of a Basic C Program**

A basic C program consists of:

* **Header Files**: Provide predefined functions (`stdio.h`)
* **main() Function**: Starting point of program execution
* **Program Statements**: Instructions to be executed
* **return 0;**: Ends the program successfully

---

### **3. `main()` Function**

The `main()` function is the entry point of a C program.
Program execution starts from `main()`.

**Example:**

```c
int main() {
    printf("Welcome to C");
    return 0;
}
```

Without `main()`, a C program cannot run.

---

### **4. Escape Characters and `\n`**

Escape characters are special characters used in strings to format output.

* `\n` creates a new line.

**Example:**

```c
printf("Hello World!\nI am learning C.");
```

---

### **5. Program to Print Given Output**

**Program:**

```c
#include <stdio.h>

int main() {
    printf("Hello World!\n");
    printf("I am learning C.");
    return 0;
}
```

**Explanation:**

* `#include <stdio.h>` enables output functions
* `printf()` prints text
* `\n` moves output to the next line
* `return 0;` ends the program

---

### **6. Importance of Semicolons and White Spaces**

* **Semicolon (`;`)** indicates the end of a statement.
* **White spaces** improve code readability and are ignored by the compiler.

**Example:**

```c
int a = 10;
int b = 20;
```

---

### **7. Creating Blank Lines in Output**

Blank lines can be created using multiple `\n`.

**Example:**

```c
printf("Hello World!\n\nI am learning C.");
```

This creates one blank line between the outputs.
