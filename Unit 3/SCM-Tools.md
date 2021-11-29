# SCM Tools

There are four types of tools:

1) **Source Code Administration Tools**: Used for source code control.
2) **Software Build Tools**: Used for building source code.
3) **Software Installation Tools**: Used for packaging and installing software.
4) **Software Bug Tracking Tools**: Used for tracking bugs and changes associated with them.

### Source Code Administration Tools

- **RCS**: Revision Control System. Only version control.
- **CVS**: Concurrent Version Control, based on RCS and allows concurrent working **without** locking.
- **ClearCase**: Multiple servers, process modelling.
- **GitHub**: Development platform where code is hosted for version control and projects can be managed.

### Software Build Tools

**Software Build**: refers to the process of converting source code files into standalone artefacts (binary or executable files) that can run on a computer. One of the important steps is the **compilation** process where source code is converted to executable code.

- **Make**: Uses *MakeFiles* to derive target program from source code.
- **CruiseControl**: Open-source tool for software builds.
- **FinalBuilder**: Has a GUI with an extensive library of scripts.
- **Maven**: Based on the concept of a Project Object Model (**POM**).

### Software Installation Tools

Install tools are cross-platform and produce installers for Windows, MacOS, etc.

- **Installer** is a computer program that installs files, drivers, and other software onto a computer. 
- **Custom Installers**: Specifically made to install files they contain.
- **General Purpose Installers**: Reading contents of software packages to be installed.
- Can use a **Bootstrapper** which is a small installer that runs first and sets up the necessary pre-requisites.
**Eg**: DeployMaster (Windows), InstallAware (Windows), InstallShield, etc.

### Software Bug Tracking Tools

It is an application that keeps track of reported bugs in software development projects. It is an **issue-tracking** system.
<br>Gives a clear, centralised view of overall development requests.