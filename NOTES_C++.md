### Notes on "Ultimate C++ - Part 1" by Mosh Hamedani

#### Getting Started
- **C++ Standard Library**: Pre-written C++ code for solving common problems.
- **Compiling**: Transforming C++ code to machine code.
- **Console Application**: Text-based programs.
- **Function**: Block of code performing a specific task.
- **Graphical User Interface (GUI)**: Visual interface for user interaction.
- **Integrated Development Environment (IDE)**: Tools for coding (e.g., Visual Studio, XCode, CLion).
- **Machine Code**: Low-level code executed by the computer.
- **Statement**: Single instruction in C++.
- **Syntax**: Rules governing the structure of C++ code.
- **Terminal**: Command-line interface.

**Example**: 
```cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!";
    return 0;
}
```

#### The Basics
- **Camel Case**: `camelCaseExample`
- **Comment**: // Single-line comment
- **Constant**: Immutable value.
- **Directive**: Instructions for the compiler (e.g., `#include`).
- **Expression**: Code that produces a value.
- **Hungarian Notation**: Prefix notation for variables.
- **Mathematical Expression**: Includes operators (+, -, *, /, %).
- **Operand**: Entity on which operators act.
- **Operator**: Symbol representing an operation.
- **Pascal Case**: `PascalCaseExample`
- **Snake Case**: `snake_case_example`
- **Standard Input Stream**: Reading data (e.g., `std::cin`).
- **Standard Output Stream**: Writing data (e.g., `std::cout`).
- **Stream Extraction Operator**: `>>`
- **Stream Insertion Operator**: `<<`
- **Variable**: Storage for data.

**Example**: 
```cpp
int age = 30; // Variable
const double PI = 3.14; // Constant
std::cout << "Age: " << age << "\n"; // Output
```

#### Data Types
- **Array**: Collection of elements.
- **Binary System**: Base-2 number system.
- **Boolean Values**: `true` or `false`.
- **Casting**: Converting one data type to another.
- **Characters**: Single letters or symbols.
- **Compile-time Error**: Error detected during compilation.
- **Data Type**: Specifies the type of data (e.g., `int`, `double`).
- **Decimal System**: Base-10 number system.
- **Floating-point Number**: Numbers with decimal points.
- **Hexadecimal System**: Base-16 number system.
- **Index**: Position in an array.
- **Overflow**: Exceeding data type limits.
- **Run-time Error**: Error occurring during execution.
- **Stream Manipulator**: Format data output.
- **String**: Sequence of characters.
- **Underflow**: Below data type limits.

**Example**: 
```cpp
int numbers[5] = {1, 2, 3, 4, 5}; // Array
bool isTrue = true; // Boolean
char letter = 'A'; // Character
float pi = 3.14F; // Floating-point
```

#### Decision Making
- **Boolean Expression**: Produces a Boolean value.
- **Comparison Operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`.
- **Conditional Operator**: Ternary operator (`condition ? true : false`).
- **If Statement**: Executes code based on a condition.
- **Logical Operators**: `&&`, `||`, `!`.
- **Nesting If Statements**: If statements within another if statement.
- **Switch Statement**: Selection statement with multiple cases.

**Example**: 
```cpp
if (age > 18) {
    std::cout << "Adult";
} else {
    std::cout << "Minor";
}
```

#### Loops
- **Break Statement**: Exits the loop.
- **Continue Statement**: Skips the current iteration.
- **Do-while Statement**: Executes at least once.
- **For Statement**: Loop with a counter.
- **Infinite Loop**: Never-ending loop.
- **Iteration**: Single pass through a loop.
- **Loops**: Repeats a block of code.
- **Loop Variable**: Variable controlling the loop.
- **Nested Loop**: Loop within another loop.
- **While Statement**: Repeats as long as a condition is true.

**Example**: 
```cpp
for (int i = 0; i < 10; i++) {
    std::cout << i << " ";
}
```

#### Functions
- **Arguments**: Values passed to a function.
- **Function Declaration**: Specifies the function’s name, return type, and parameters.
- **Function Definition**: Contains the actual code.
- **Function Overloading**: Multiple functions with the same name but different parameters.
- **Return Statement**: Ends function execution and optionally returns a value.

**Example**: 
```cpp
int add(int a, int b) {
    return a + b;
}
std::cout << add(3, 4); // Output: 7
```

This is a concise summary maintaining the structure and key points from the original document, with examples to illustrate the concepts.
