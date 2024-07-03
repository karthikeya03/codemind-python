```markdown
# The Ultimate C++ Course: Part 1 - The Fundamentals
*by Mosh Hamedani*

---

## Table of Contents
1. [Getting Started](#getting-started)
2. [The Basics](#the-basics)
3. [Data Types](#data-types)
4. [Decision Making](#decision-making)
5. [Loops](#loops)
6. [Functions](#functions)

---

## Getting Started

### Terms
- **C++ Standard Library**: A collection of pre-written C++ code.
- **Compiling**: Converting C++ code to machine code.
- **Console Application**: A program that runs in a terminal or command prompt.
- **Function**: A block of code that performs a specific task.
- **Graphical User Interface (GUI)**: A visual way to interact with a computer.
- **Integrated Development Environment (IDE)**: Software for writing and testing code.
- **Machine Code**: Low-level code that a computer's processor understands.
- **Statement**: A single instruction in a program.
- **Syntax**: The rules that define the structure of a programming language.
- **Terminal**: A text-based interface to interact with the computer.

### Summary
- C++ is a powerful language known for its performance and efficiency.
- Commonly used for performance-critical applications, such as video games (e.g., Unreal Engine), servers, and operating systems.
- Learning C++ involves understanding its syntax and the C++ Standard Library.
- Popular IDEs for C++ include MS Visual Studio, XCode, and CLion.
- C++ programs start with the `main()` function.

---

## The Basics

### Terms
- **Camel Case**: `camelCaseExample`
- **Comment**: `// This is a comment`
- **Constant**: A value that does not change.
- **Directive**: `#include <iostream>`
- **Expression**: `5 + 3`
- **Hungarian Notation**: `int nValue`
- **Mathematical Expression**: An expression that includes operators like `+`, `-`, `*`, `/`, `%`.
- **Operand**: The values involved in an operation.
- **Operator**: Symbols like `+`, `-`, `*`, `/`, `%`.
- **Pascal Case**: `PascalCaseExample`
- **Snake Case**: `snake_case_example`
- **Standard Input Stream**: `cin`
- **Standard Output Stream**: `cout`
- **Stream Extraction Operator**: `>>`
- **Stream Insertion Operator**: `<<`
- **Variable**: A storage location identified by a name.

### Summary
- Variables store data temporarily in memory. Declare with a type and name (e.g., `int age`).
- Constants are unchangeable once set (e.g., `const int DAYS_IN_WEEK = 7`).
- Naming conventions: PascalCase, camelCase, snake_case.
- Expressions produce values (e.g., `2 + 2`).
- `cout` and `cin` are used for output and input, respectively.
- Use `#include` to include files from the Standard Library.
- Comments explain code and assumptions.

### Example
```cpp
#include <iostream>
using namespace std;

int main() {
    int age = 30; // Variable declaration and initialization
    const int DAYS_IN_WEEK = 7; // Constant declaration
    cout << "Age: " << age << endl;
    return 0;
}
```

---

## Data Types

### Terms
- **Array**: A collection of elements.
- **Binary System**: Number system using base 2.
- **Boolean Values**: `true` or `false`.
- **Casting**: Converting one data type to another.
- **Characters**: `char`, e.g., `'A'`.
- **Compile-time Error**: Errors detected during compilation.
- **Data Type**: Type of data a variable can hold.
- **Decimal System**: Number system using base 10.
- **Floating-point Number**: Numbers with decimal points.
- **Hexadecimal System**: Number system using base 16.
- **Index**: Position of an element in an array.
- **Overflow**: When a value exceeds the storage capacity.
- **Run-time Error**: Errors detected during program execution.
- **Stream Manipulator**: Functions to format data.
- **String**: A sequence of characters.
- **Underflow**: When a value is too small for its storage type.

### Summary
- C++ has data types for integers, floating-point numbers, characters, and Booleans.
- Default types: `double` for floating-point, `int` for integers.
- Use `auto` to let the compiler infer the type.
- Numerical systems: decimal, binary, hexadecimal.
- Use `sizeof()` to check data type size.
- Boolean `false` is `0`, any non-zero is `true`.
- Strings are sequences of characters.
- Arrays store sequences of items.

### Example
```cpp
#include <iostream>
using namespace std;

int main() {
    int numbers[] = {1, 2, 3, 4, 5}; // Array of integers
    cout << "First element: " << numbers[0] << endl;
    return 0;
}
```

---

## Decision Making

### Terms
- **Boolean Expression**: Produces `true` or `false`.
- **Comparison Operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`.
- **Conditional Operator**: `? :`
- **If Statement**: Executes code based on a condition.
- **Logical Operators**: `&&`, `||`, `!`.
- **Nesting If Statements**: `if` within another `if`.
- **Switch Statement**: Selects code to execute based on a variable.

### Summary
- Comparison operators compare values.
- Boolean expressions result in `true` or `false`.
- Logical operators combine Boolean expressions.
- `&&` requires both conditions to be true.
- `||` requires at least one condition to be true.
- `!` inverts a Boolean value.
- `if` and `switch` control program logic.
- Use `else if` and `else` with `if` for additional conditions.
- Nesting `if` statements for complex conditions.
- Conditional operator simplifies `if/else`.
- `switch` compares a variable to multiple values.

### Example
```cpp
#include <iostream>
using namespace std;

int main() {
    int score = 85;

    if (score >= 90) {
        cout << "Grade: A" << endl;
    } else if (score >= 80) {
        cout << "Grade: B" << endl;
    } else {
        cout << "Grade: C" << endl;
    }

    return 0;
}
```

---

## Loops

### Terms
- **Break Statement**: Exits a loop.
- **Continue Statement**: Skips to the next iteration.
- **Do-while Statement**: Executes code at least once.
- **For Statement**: Loop with a counter.
- **Infinite Loop**: A loop that never ends.
- **Iteration**: Each pass through a loop.
- **Loop Variable**: Controls the number of iterations.
- **Nested Loop**: Loop inside another loop.
- **While Statement**: Loop with a condition.

### Summary
- Loops repeat a set of statements.
- Types: `for`, range-based `for`, `while`, `do-while`.
- `for` loops for known iteration counts.
- Range-based `for` loops for iterating over collections.
- `while` and `do-while` for unknown iteration counts.
- `break` exits loops.
- `continue` skips an iteration.

### Example
```cpp
#include <iostream>
using namespace std;

int main() {
    for (int i = 0; i < 5; i++) {
        cout << "Iteration: " << i << endl;
    }
    return 0;
}
```

---

## Functions

### Terms
- **Debugging**: Identifying and fixing errors.
- **Function**: A group of statements performing a task.
- **Function Arguments**: Values passed to a function.
- **Function Declaration**: Declares a function's existence.
- **Function Definition**: Provides the function's code.
- **Function Parameters**: Variables in a function's signature.
- **Function Prototype**: Another term for function declaration.
- **Function Signature**: Includes name, parameters, and types.
- **Global Variables**: Accessible throughout the program.
- **Invoking a Function**: Calling a function.
- **Header Files**: `.h` or `.hpp` files with declarations.
- **Local Variables**: Accessible only within a function.
- **Namespaces**: Prevent name collisions.
- **Overloading Functions**: Multiple functions with the same name but different signatures.

### Summary
- Functions perform specific tasks and should be clear in purpose.
- Functions can have zero or more parameters and can be overloaded.
- Arguments are passed by value or reference.
- Local variables are scoped to the function; global variables are accessible everywhere.
- Header files contain declarations; implementation files contain definitions.
- Use namespaces to avoid naming conflicts.
- Debugging involves stepping through code to find errors.

### Example
```cpp
#include <iostream>
using namespace std;

// Function declaration
void greet();

int main() {
    greet(); // Function call
    return 0;
}

// Function definition
void greet() {
    cout << "Hello, World!" << endl;
}
```
```

