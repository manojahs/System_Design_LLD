# System_Design

```
System design is the process of defining the architecture, components, modules, interfaces, and data for a system to satisfy specific requirements

LLD
-------
LLD is the blueprint that guides developers on how to implement specific components of a system, such as classes, methods, algorithms, and data structures.

Low-level design (LLD) is the detailed blueprint for building specific components: classes/modules, function signatures, database schemas, state machines, algorithms, error handling, retries/timeouts, validation, and detailed API request/response models. It focuses on “how exactly we implement it” inside a service/module—down to design patterns, sequence diagrams, edge cases, and test strategy. The output is often detailed design docs, pseudo-code/specs, schema definitions, and sometimes tickets that engineers can implement directly.

* Clear layers (API/Application/Domain/Infrastructure) and dependency direction inward
* DI-friendly design (interfaces at boundaries)
* Domain rules enforced in code (not only in controllers)
* EF Core mapping doesn’t dictate your domain shape
* Explicit handling of concurrency, retries, idempotency, and validation
* Test strategy aligned to boundaries

The software architecture impacts:
  Performance and scale of product
  Ease of adding new features
  Response to failure or Security back

The software architecture of a system is a high level description of the system structure, its different component, and how those components
communicate with each other to fullfill the systems requirement and constraints

Technologies or programming languages are not part of the software architecture but a part of the implementation but it wll be part
of implementation.

Software development life cycle
--------------------------------
Desgn -> Development -> Testing -> Deployment
Design is nothing but building software architecture

Software Arch is the output of design phase and input to the implementation

Scalability
----------------
Its the measurement of system ability how it handle the growing amount of work, in a easy and cost effective by
adding resources to the system.








```
