# Software Configuration Management

- **SCM** is the process to **systematically organise, manage and control** changes in the documents, code and other entities which are outcomes of different phases of the Software Eng process.
- Goal is to increase productivity by increased coordination between members of a team leading to less confusion and mistakes.
- Involves identiftying individual elements and configurations, tracking changes and version selection among others.

### Why is SCM necessary?

- Multiple people working on the project simultaneously and updating the same.
- Working on more than one version of the software.
- Working on released systems.
- Changes in configuration items due to change in user requirements, budgets, schedule, etc.
- Code/software must run on different OSs.
- Controlling costs involved in making changes to the system.

### SCM in Scrum-Agile

SCM is the responsibility of the **whole team** and needs to be automated as much as possible.

- **Definitive** versions of the project are held in a shared repository.   
- Developers copy this to their own workspace, make changes to code and a new system is built on their computer for testing.
- Once the developer is happy with the changes made, modified version is returned to the project repository, making it available to other team members.

### Benefits of SCM

- Permits orderly development.
- Orderly release of new/revised software.
- Only **approved changes** to new and existing software is implemented and deployed.
- Ensures documentation accurately reflects updates.
- Prevents unauthorized changes from being made.

### Configuration Management Roles

- **Configuration Manager**: Responsible for identifying configuration items and defining the procedures for promoting and creating new releases.
- **Change Control Board (CCB) Member**: Responsible for approving and rejecting changes.
- **Developer**: Creates versions triggered by change requests. Checks in changes and resolves conflicts.
- **Auditor**: Responsible for validating the processes followed for selection and evaluating promotions for release. Ensures consistency and completeness of the release.