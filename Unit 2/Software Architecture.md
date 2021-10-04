# Software Architecture

**Software Architecture** is the decomposition of software into various components along with how these components interact with each other.

Can be used for communication among the stakeholders. It is a **blueprint** for the system under construction.

Supports reuse at an architectural level like CBSE or Product Lines where systems can be built using externally developed elements.

Changes to architecture is expensive in later stages of SDLC.

Characteristics of Software Architecture are:

- Address variety of stakeholder perspectives.
- Realises all use cases for the problem.
- Quality-driven.
- Recurring architectural styles and patterns.
- Separation of concerns.

Factors that influence Software Architecture:

- Functionality
- Cost
- Audience
- Dependencies and Integration
- Background skill required
- Initial State
- Business Priority

## Software Decomposition

#### Based on Layering

Ordering the system based on different layers such as UI, backend, etc.

#### Based on Distribution of Computational Resources

- Dedicated task owning a thread and hence some processes not needing to wait for thread allocation.
- Done for greater fault isolation.
- Distribution of separation of concern with redundancy leading to high availability.

#### Decomposition based on Exposure

- Decomposition done on how the component is **exposed**, and what services it consumes.

#### Decomposition based on Functionality

- Decomposition done on the features or functionality provided. Done by grouping within the problem domain.

#### Decomposition based on Generality

- Trying to understand which components can be used in other places as well.

### Other approaches to Decomposition

- **Divide and Conquer**: Divide complex problem into smaller steps.
- **Stepwise Refinement**: Start with simple solution and enhance it step by step.
- **Top-Down**: Start with overall view and then go to subsytems.
- **Bottom-Up**: Start with individual elements and then compose them together.
- **Information Hiding**: Separation of information from implementation.


## Architectural Views

Ways of describing the architecture, enables different stakeholders to see different views of the system. 

### Structure of Modules

- **Modules** are units of code having their own functionality.
- Stucture the system as a set of modules.
- Architect decides what each unit of code will do and assigns it to a module.
- Used as basis for project organisation and documentation.
- Larger modules can be broken into smaller modules as and when necessary.

### Component and Connector Structure

- **Component** or **Processing Element** software that connects input to outputs. Could do a computation, or act as a server. (I think it's just a component in a system?)
- **Data** is the information to be processed or that has already been processed.
- **Connecting Element** connects the components and the data.

### Allocation Structure

- **Deployment Structure** shows how software is assigned to hardware and what communication paths are used. Allows engineer to reason out performance, data integrity, security, among others.
- **Implementation Structure** shows how software is mapped to file system in various system environments.
- **Work Assignment** shows how work is assigned and what knowledge is neede where.

### Kruchens (4 + 1) View

TODO


## Architecture Styles

It is a pattern of organisation of components and can be identified by features that make it notable (worthy of attention).

It is a way of organising modules.

Addresses the structure and behaviour of the system (think about historical monuments and their style relating to their region).

Provides the following:

- **Vocabulary**: set of elements such as clients, servers, pipes, etc.
- **Design Rules**: defines how various componenets are connected to each other.
- **Semantics**: well-defined meaning to why the components are connected the way they are.
- **Analysis**: styles provide analytics that can be done on systems built that way such as deadlock detection, scheduling, etc.

Similar to [Components and Connectors](#Component-and-Connector-Structure).

## Architecture Patterns

Proven approach of structuring and functioning of subsystems which has been used earlier and known to work for given problem.

Potential solution to a recurring problem.

#### Monolithic or Single-Tiered Architecture

- Contains single layer with UI, manipulation of data and logic all in one. Eg: Microsoft Word

#### Two-Tiered Architecture

- User interface is part of the client system.
- Business rules and data retrieval/manipulation is performed by a separate application, often on a physically different system.

Eg: Client-Server Applications

#### Three-Tiered Architecture

- User interface, business layer (or the logic) and database are separate.
- User interface just consists of the **display**.
- Functionalities are provided through the **business layer** or **logic**.
- Data is stored (persistent) in the **data tier**.
