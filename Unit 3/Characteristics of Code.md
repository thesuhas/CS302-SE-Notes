# Characteristics of Code

Different characteristics of code are:

### Program should be simple and clear

Programs should be well thought out, well structured and should not fall prey to a programmer's tendency to jump start.

There shouldn't be **too many**:

- Lines per function
- Functions per file
- Arguments per function
- Conditions

### Naming and Naming Conventions

Names should be meaningful and **not** be close to keywords.
Should have **descriptive** names and good to use 2-3 character long names.

Different conventions of naming are:

- **Pascal Casing**: First Letter of each word is Upper Case and the rest are Lower Case. 
Eg: **B**ack**C**olour

- **Camel Casing**: First letter of each word is upper case (**except the 1st word**) and the rest of the letters are Lower Case.
Eg: **b**ack**C**olour

- **Underscore Prefix**: Start with underscore and then precede to use Camel Case.
Eg: **_**back**C**olour

Naming conventions to **maximise portability** across compilers:

- Variable name **should not** be a keyword in a given programming language.
- Variable **should not** have a name that starts with an **underscore(_)**.
- Should **not** be longer than **31 characters**.
- Should not contain any **numeric** value that is **called out** elsewhere. 
**Eg:** Number of elements in an array or number of bits in the type of the variable.
- **Should** be **descriptive**.

[Source](https://barrgroup.com/embedded-systems/books/embedded-c-coding-standard/variable-rules/naming-conventions)

### Structuring

It refers to the dependencies between software components. They can be highlighted through proper naming and layout.

**File Structure**:

- Can be logically grouped into various header files.
- Needs to be well partitioned into the proper header files. Need to decide what variables and functions are exposed and what are not.

### Ease of Reading and Understanding

It is dependent on the visual layout of the code. Using **standardised indentation** (like in python) is used to illustrate the heirarchies in a program.
<br>
Comments should **explain and clarify** the code and **NOT** be a **repeat of the code** itself. Should explain the underlying logic in a clean and concise manner.

### Coding Standards

- They are rules that are **mandatory**. Provides a **uniform appearance** to code written by different engineers.
- Improves readability, maintainability and reduces complexity.
- Some of the practices followed are :

    - **Defensive** programming.
    - **Testable** programming.
    - **Secure** programming.

- Helps in **code reuse**. 
- Improves efficiency of programmers and promotes sound programming practices.

Examples:

- Standard Headers for modules which can contain
    
    - Name
    - Date of creation
    - Synopsis of module and what it does
    - Functions supported along with input and output parameters
    - Global variables accessed

- Different types of naming conventions for local and global variables.
- Error return and exception handling conventions.

#### Defensive Programming

**Murphy's Law**: If anything can go wrong, it will.
<br>Redundant code is incorporated to check system state after modifications.
<br>Implicit assumptions are tested explicitly.

#### Secure Programming

Process of developing computer software in a way that guards against the **accidental** introduction of security vulnerabilities. Defects, bugs and flaws in logic are the primary cause of security vulnerabilities.

Practices that can avoid these are:

- **Validate Input**: validate input from all untrusted data sources.
- **Heed Compiler Warnings**: Compile code using the **highest** warning level and modify your code by addressing these warnings. Use static and dynamic analysis tools to detect and eliminate additional security flaws.
- **Default Deny**: Access decisions are based on permission. By default access is denied and certain identified accesses are permitted.
- **Principle of Least Priviledge**: Every process should execute with the least set of priviledges required. Elevated priviledge should only be given for the least amount of time required to complete the task.
- **Sanitise data**: Sanitise **all data** sent to systems such as command shells, relational databases and Commercial Off-the-Shelf Components (COTS).

### Coding Guidelines

- Recommended to be followed and are **not** mandatory.
- Gives a uniform appearance to code written by different engineers.
- Most guidelines are **generic** regarding the coding style that **helps in readability**.
- Helps in detecting errors in the early phases of the project.

### Refactoring Code

- Improving the **internal structure** of the code while preserving its external behaviour.
- It is intended to:

    - Design and structure the implementation of the software while retaining its functionality.
    - Improves objective attributes of code such as length and duplication that improve ease of maintenance.
- It is **NOT** rewriting code, fixing bugs or improving observable aspects such as interface.