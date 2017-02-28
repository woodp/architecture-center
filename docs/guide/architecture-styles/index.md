# Architecture styles

We use the term *architecture style* to mean a family of architectures that share certain characteristics. *N-tier application* and *microservices application* are two examples of architectural styles. 

An architecture style is an abstraction that defines high level concepts and a shared vocabulary. For example, the N-tier architecture styles defines the concept of a *tier*, and the microservices architecture style defines the concept of a *microservice*. By creating a shared vocabulary, it is easier to understand and reason about the architecture.

The choice of an architectural style does dictate a particular technology. However, certain technologies are more naturally suited for some architectures. For example, container orchestrators are a natural fit for microservices architectures. So the choice of architectural style informs the choice of technologies. 

Architectural styles as constraints. The high-level concepts in an architectural style impose a set of constraints on the architecture. These contraints guide the design and create a "shape." The hope is that by conforming to these constraints, certain desirable properties will emerge. Therefore it’s important to understand not just the constraints (the "shape" of the architecture) but the motivation behind them.

For each architecture style, we include the following:

- A description of the architecture.
- A logical diagram showing the important parts of the architecture.
- Recommendations for when to choose this architecture style, including benefits and challenges.
- A diagram showing a recommended deployment of this architecture, including the relevant Azure services and resources.
