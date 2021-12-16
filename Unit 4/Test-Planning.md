# Test Planning

## 1. Scope

- Reviewing the use case scenario in the deployment environment
- Discussing with designer and developer
- Reviewing project documentation
- Need to define what is *in-scope* testing and what is *out of scope* testing as cannot test for all possible combinations.

## 2. Test Adequacy

- Testing a subset of possible combinations does not guarantee absence of issues.
- Issues could be found during testing, the closing of which may not be feasible before the product is released to the customer.
- **Test Adequacy** describes criteria that can be used to determine when to stop testing or when testing is completed for that iteration.

## 3. Test Strategy

- It is the test approach, defines how the test will be carried out.
- Determines type of tests and test environment, automation strategy and tools, risk analysis, etc.

### Testing Models

#### Demonstration Model

- Make sure software runs and solves the problem.
- If software passes all the test cases, satisfies the specifications.
- May unconciously only test what may succeed.

#### Evaluation Model

- Detects faults through lifecycle phases.
- Focuses on analysis and review techniques to detect faults.

#### Destruction Model

- Try to make the software fail and find as many faults.
- Good test cases are those that find faults.
- Difficult to know when to stop as do not know how many faults are left.

#### Preventive Model

- Prevents faults in early phases through careful planning and design.
- Reviews and Test-Driven Development.

### Test Execution Environment

- It is a **test bed** of software and hardware for the testing team to execute test cases.
- Configured as per need of the application undergoing testing.
- Setting up the right test bed is critical to ensure success of software testing and preventing delays, cost escalations and incorrect conclusions.
- Needs proper planning on resource usage, remote environment, setup time, etc.

### Tools being used

- Application under Testing (AUT) needs to be compatible with the testing tool.
- Testers need to be comfortable with the tool.
- Need to find the right balance between features, ability to generate reports and data for stakeholders.
- Cross platform support is a necessity due to the need to run tests on different environments.
- Cost is also a factor
- Opensource or proprietary has to be decided as well.

## 4. List of Deliverables

- List of deliverables needs to be identified. This includes

    - Test specifications for each module
    - Test cases for different applications

## 5. Test Schedule

- Creation of a detailed test schedule.
- Estimation for buliding test strategy
- Include WBS

## 6. Planniing, Identification and Allocation of Resources

- Done in tandem with previous step or iteratively to ensure that the schedule is taken into account while allocating resources.
- Identifying the number and type of servers, storage, tools, etc.
- Identifying the kind and number of people working on the project.
- Identifying the test environment.
- After identification and allocation of resources is done, schedule is reworked.

## 7 & 8. Identification of the Milestones and Risks

- Project milestones are identified given the deliverables and the schedule.
- Risk for completion of each task is identified, analysed and risk-mitigation plans and triggers are made.
- Milestones are used to track overall progress and help identify triggers.

## 9. Measures and Metrics

- Measurements will be made from number of test cases planned, created and run, time spent, etc.
- Metrics like `test cases/day`, `issues/KLoC`, `critical issues/KLoC`, etc.