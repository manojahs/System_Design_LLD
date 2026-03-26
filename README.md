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

1) Horizontal Scalability (scale up/down)
2) Vertical Scalability (scale out/in)
3) Team/Org Scalability

Vertical scaling
-------------------
Adding Resources/Upgrading the existing resources on a single computer, to allow our system to handle higher traffic or load.

Pros
   Any application can benefit from it
   No code changes are required
   Migration between different machines is very easy

Cons
  The scope update is limited
  

Horizontal Scaling
-------------------
Adding more resources in a form of new instances running on different machines to allow our system to handle higher traffic or load.

Pros
  No limit on scalability
  Its easy to add/remove machines
  If designed correctly we get
     High Availability
     Fault Tolerance

Cons
   Initial code changes may be required
   Increased complexity, coordination overhead

Team/Org Scale
----------------
The measure of system ability to handle growing amount of work in an easy and cost effective way by adding resources to the system
or increasing the productivity while hiring more engineers into the team

RPC
-------
Remote Procedure Call
 -> It support multiple programming lang
 -> Application written in different programming lang can talk to each other using RPC





```
