# Introduction to Software Testing

- Testing is a phase which **follows** requirements, architecture, design and implementation.
- It is the phase in which Verification and Validation are done.

    - **Verification**: It is the process of checking whether the product is meeting the specified requirements.
        
        - It is checking whether the **product is being built right**.

    - **Validation**: It is the process of evaluation a system to determine whether the **right product is being built**.

- Testing establishes that the product behaves as expected and exposes any deviations from desired behaviour, if any.
- Testing involves measuring attributes such as performance and usability, operational reliability, etc.
- **Builds confidence** that it is good enough for intended use. Planned usage determines the degree of confidence necessary and degree of testing.

## Objectives of Testing

- **Demonstration**: Show that system can be used with **acceptable risk**. Demonstrate functions under special conditions.

    - Show that products are ready for integration/use.

- **Detection**: Discover defects, errors and deficiencies. 

    - Determine system capabilities and limitations.
    - Determine the quality of the product and its components.

- **Prevention**: Provide info to prevent/reduce the number of errors.

    - Reduce the number of errors **propagated to later stages**.
    - Clarify system specifications and performance.


## Verification

*Are we building the product right*

- It is the process of checking whether the product being built meets the specified requirements.
- Doest **not** involve testing of code.
- Finds bugs **early** in the development cycle.
- It is **Static testing**, code is not executed.
- Happens **before validation**.

## Validation 

*Are we building the right product*

- Determines if the system/product meets the consumer requirements.
- Done through **Dynamic Testing**. Involves the execution of code and is done by the testing team.
- Done **after verification**.

## Terms

- **Defect**: Deviation from the requirements.

    - Due to design mistake or a code mistake.

- **Bug**: Coding error that prevents it from working as intended. 

    - Programmer's mistake.

- **Failure**: State of system due to a defect where it is unable to perform as intended.

    - Occurs during development life cycle or later.

- **Issue**: Raised by user/customer when the product does not work as intended with respect to functionality or performance.

    - Tracked.