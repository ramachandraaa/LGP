# C Language Introduction

C is a **general-purpose procedural programming language** known for its **efficiency** and **low-level memory access**. It is widely used in:

- System Programming
- Embedded Systems
- Performance-Critical Applications

C is popular because of its:

- High Speed and Performance
- Portability Across Platforms
- Close Interaction with Hardware
- Efficient Memory Management

Due to these features, C serves as the foundation for many modern programming languages and operating systems.

<p align="center">
  <img src="https://raw.githubusercontent.com/ramachandraaa/LGP/refs/heads/main/FeatuersOfC.png" alt="Features of C Language" width="700">
</p>

# Writing First Program in C Language

This simple program demonstrates the basic structure of a C program.

```c
#include <stdio.h>

int main(void)
{
    // This prints "Hello World"
    printf("Hello World");

    return 0;
}
```

## Output

```text
Hello World
```

---

# Structure of C Program

| Line | Code | Description |
|------|------|-------------|
| 1 | `#include <stdio.h>` | Header File |
| 2 | `int main(void)` | Main Function |
| 3 | `{` | Beginning of Program Body |
| 4 | `// prints "Hello World"` | Comment |
| 5 | `printf("Hello World");` | Statement |
| 6 | `return 0;` | Return Statement |
| 7 | `}` | End of Program Body |

## Components of a C Program

- **Header Files** → Used to include standard library functions.
- **Main Function** → Starting point of every C program.
- **Comments** → Used to explain the code.
- **Statements** → Instructions executed by the compiler.
- **Return Statement** → Ends the program execution.
