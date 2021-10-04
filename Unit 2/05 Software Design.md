# Software Design

- Design is the smaller picture of implementation methodology (architecture is bigger picture), with local constraints on different parts of the system.

- Design faces implementation (architecture is strategy), is more concrete.

- Design is internal to a system (architecture is external) and focuses on problem solving.

- Design has more influence on functional requirements (arch is non-functional).

Detailed design involves:

- Further decomposition of products being developed.
- Identification and description of the behaviour of sub-components.
- How interfaces are going to be built using algorithms and data structures.
- How system will facilitate user interaction via UI.

## Design Enabling Techniques

#### Abstraction

Focuses on essential properties and ignores details that are not relevant for the problem and hence reduces the complexity.

#### Modularity, Cohesion and Coupling

**Modularity**: extent to which overall system and be broken down into smaller modules.

**Cohesion**: Extent to which modules are dependent on/fit into each other. Needs to be **strong**.

**Coupling**: How strongly one module is connected to one another. Change of one module impacts the others. Needs to be **loose**.

#### Information Hiding

**Encapsulation**: Hides data and allows access only through specific functions/methods.

**Separation of Implementation and Interface**: Allows us to change implementation without touching interface.

#### Limiting Complexity

**Complexity** is the amount of effort required to build the solution to a problem.

**Intra-modular**: Complexity of a single module is based on size (Lines of Code).

**Inter-modular**: Complexity between different modules. Based on size and various other measures.