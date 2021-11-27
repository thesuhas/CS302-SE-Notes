# Characteristics of Code

Different characteristics of code are:

#### Program should be simple and clear

Programs should be well thought out, well structured and should not fall prey to a programmer's tendency to jump start.

There shouldn't be **too many**:

- Lines per function
- Functions per file
- Arguments per function
- Conditions

#### Naming and Naming Conventions

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

#### Structuring

It refers to the dependencies between software components. They can be highlighted through proper naming and layout.

**File Structure**:

- Can be logically grouped into various header files.
- Needs to be well partitioned into the proper header files. Need to decide what variables and functions are exposed and what are not.

#### Ease of Reading and Understanding

It is dependent on the visual layout of the code. Using **standardised indentation** (like in python) is used to illustrate the heirarchies in a program.
<br>
Comments should **explain and clarify** the code and **NOT** be a **repeat of the code** itself. Should explain the underlying logic in a clean and concise manner.