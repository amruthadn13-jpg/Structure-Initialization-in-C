# Structure Initialization in C

## Overview

This project demonstrates **structure initialization in C**, where values are assigned to structure members at the time of declaration. This approach simplifies code and makes structure creation more efficient.

The program creates a structure variable, initializes all members in a single statement, and displays the stored data.

---

## Concepts Covered

- Structures (`struct`)
- Structure initialization
- Character arrays (strings)
- Structure variables
- Member access using the dot (`.`) operator
- Formatted output using `printf()`

---

## Project Description

The program defines a structure named `myStructure` containing:

- An integer member (`myNum`)
- A character member (`myLetter`)
- A string member (`myString`)

Instead of assigning values separately, all members are initialized during structure declaration.

---

## Structure Definition

```c
struct myStructure {
    int myNum;
    char myLetter;
    char myString[30];
};
```

This structure groups different data types into a single user-defined data type.

---

## Structure Initialization

```c
struct myStructure s1 = {13, 'B', "Some text"};
```

Here:

- `13` is assigned to `myNum`
- `'B'` is assigned to `myLetter`
- `"Some text"` is assigned to `myString`

This method initializes all structure members in one statement.

---

## Sample Output

```text
13 B Some text
```

---

## Learning Outcomes

- Understanding structure initialization
- Working with multiple data types in a structure
- Storing string data inside structures
- Accessing initialized structure members

---

## Real-World Applications

- Student Information Systems
- Employee Records Management
- Banking Applications
- Inventory Tracking Systems
- Embedded Systems
- Configuration Data Storage

---

## Time Complexity

```text
O(1)
```

Accessing structure members takes constant time.

---

## Space Complexity

```text
O(1)
```

A fixed amount of memory is allocated for the structure variable.

---

## Key Takeaway

Structure initialization allows multiple members to be assigned values during declaration, resulting in cleaner, more readable, and efficient code.

---

## Author

**Amrutha D N**
