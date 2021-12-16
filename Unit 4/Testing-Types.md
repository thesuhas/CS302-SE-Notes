# Types of Testing

![Types](./Images/types.png)

Testing can be characterised based on Functional and Structural approaches taken.

## Black Box Testing (Functional)

![Black Box](./Images/black-box.png)

- Treats the software as a black box without any regard to the internal logic or implementation.
- Concerned with the **external** behaviour.
- Objective is to find defects in output as a result of both valid and invalid inputs.
- Testing from **user's point of view**.

## White Box Testing (Structural)

![White Box](./Images/white-box.png)

- Takes into account internal logic and structure.
- Uses knowledge of internal structure to derive test cases.
- Test cases cannot be written till the code is written (unlike Black-Box).
- Testing from a **developer's point of view**.
- Tester needs programming skills.

## Grey Box Testing (Hybrid of Functional and Structural)

![Grey Box](./Images/grey-box.png)

- Involves having access to internal algorithms and data structures to design the test cases.
- Testing is done at the **black-box level** or the **user-level**.

## Static Testing

- Detect defects in the software without actually running the code.
- Done in the earlier stages of development and can be fixed easily.

## Dynamic Testing

- Code is executed to analyse the behaviour.
- Input values are provided, output values is analysed for the observation.
- Can find difficult and complex issues that static analysis cannot.
- Time and Budget consuming.

Different kinds of Dynamic Testing like:

- Code or Fault based
- Approach used for testing
- Manual or Automatic
- Levels of Testing

### Code-Based Approaches

#### Control-Flow Testing

- A control-flow path is generated, which is a graphical representation of all the paths that a program can take during its execution.
- **Branch Coverage** where each path is executed at least once.

#### Data-Flow Testing

- Selects paths through the program's control flow in order to explore sequences of events related to the status of objects and variables.
- **Statement Coverage** where each statement is executed at least once.

### Fault-Based Approaches

#### Error Guessing

- Most plausible faults.
- Uses historical information and experience.

#### Fault Seeding

- Fault is injected into a copy of the code and tests are run.
- Other detected faults are also analyzed.

#### Mutation Testing

- Tests **seldom-executed** code.
- Single statement is changed multiple times to create mutants.
- Tests are run against original and mutants.
- All mutants should fail, in case any of the mutants pass, the test case is not good enough.

### Approach-Based

#### Specification-Based

- Tests the functionality of the system according to the specified requirements.
- Test the behaviour (output) of a system given a specific input.

#### Equivalence Partitioning and Boundary Value Analysis

- **Very important** as they can reveal **entire classes** of errors and reduce the number of test cases that must be developed and executed.

###### Equivalence Paritioning

- Divides input data into partitions of data from which test cases can be derived.
- Test cases are derived from each partition of the data.

##### Boundary Value Analysis

- Designed to include representatives of boundary values as they are common locations for errors that can result in software faults.

#### Intuition-Based

- Based on tester's experience (and intuition) of designing test cases for the product.

#### Usage Based

- Finds defects which *could be* revealed by user as they interact with the product.

#### Application Domain

- Use specific knowledge about the product domain to develop the test cases.

### Manual and Automatic Testing

#### Manual Testing

- Involves a human performing the tests step-by-step, **without** test scripts.
- Used for testing **complex tests** where automation can be expensive.
- Slow and tedious.
- Hard to get test coverage.

#### Automated Testing

- Involves tests which are executed **without** human assistance, done via test automation frameworks, along with other tools and software.
- Needs coding, test framework maintenance but is fast and repeatable.
- Most efficient for tests which need **periodic** running.