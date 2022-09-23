## Use Case Diagrams

Functional requirement:
    functions that has an effect on the system.
    

Non-Functional Requirement:
    For example background color. Not detremental to the system.
    
The purpose of a use case is to define a piece of coherent behavior without revealing the internal structure to the subject.

Help visualize the functional requirements of a system, including the relationship of "actors" to the essential processes, as well as the relationships among different use cases.

Further interactions can be defined as statechart diagrams, sequence diagrams, communication diagrams, or informal text descriptions. Don't crowd this diagram.

The pieces of interactive functionality are called use cases.

System boundary: A system boundary defines the scope and limits of the system. It is shown as a rectangle that spans all use cases of the system.

An actor is a concious or non-concious "being" outside the system that acts upon the system. 
An actor is an idealization of a role played by an external person, process or thing interacting with a system, subsystem or class.

Use cases are drawn as ovels.

Use Case: Every business functionality is a potential use case. The use case should list the discrete business functionality specified in the problem statement.

Generalization: Gerenalization of an actor means that one actor can inherit the role of the other actor. The descendant has one or more use cases that are specific to that role.

Associations: A line between actors and use cases. In complex diagrams, it is important to know which actors are associated with which use cases.

Include: Include relationship represents an invocation of use case by another use case. From a coding perspective, it is like one function being called by another function.

Extend: This relationship signifies that the extended use case will work exactly like the base use case, except that some new steps will be inserted in the extended use case. The extending use case is usually optional and can be triggered conditionally. The extended base use case must be meaningful on it's own. Extend is a "May". (login) <--- (show error message)

Include: Include relationship represents an invocation of one use case by another use case. The base use case is incomplete without the included use case. The included use case is mandatory, not optional. Include is a "Need to". (login) ---> (verify password)

