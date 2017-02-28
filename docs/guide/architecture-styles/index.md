# Architecture styles

We use the term *architecture style* to mean a family of architectures that share certain characteristics. *N-tier application* and *microservices application* are examples of architecture styles. 

An architecture style is an abstraction that defines high-level concepts and a shared vocabulary. For example, an N-tier architecture includes the concept of a *tier*, and a microservices architecture includes  the concept of a *microservice*. Shared concepts and vocabulary make it is easier to understand and reason about the architecture.

The choice of an architecture style does not dictate a particular technology. However, certain technologies are more naturally suited for some architectures. For example, container orchestrators are a natural fit for microservices architectures. So the choice of architecture style informs the choice of technologies. 

**Architecture styles as constraints**. The high-level concepts in an architecture style impose a set of constraints on the architecture. These contraints guide the design and create a "shape." The hope is that by conforming to these constraints, certain desirable properties will emerge. Therefore it’s important to understand not just the constraints (the "shape" of the architecture) but the motivation behind them.

... for example ...

## Catalog of architecture styles

- Big compute
- Big data
- CQRS
- Event driven
- Microservices
- [N-tier](./n-tier)
- [Web-queue-worker](./web-queue-worker.md)

For each architecture style, we include the following:

- A description of the architecture.
- A logical diagram showing the important parts of the architecture.
- Recommendations for when to choose this architecture style, including benefits and challenges.
- A diagram showing a recommended deployment of this architecture, including the relevant Azure services and resources.

