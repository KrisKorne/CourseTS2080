### Class Diagrams
#### Description:
Describes the types of objects that can be created.
Attributes of the classes. Any variable that is bound in a class.
Operations of class that occur.
Relationships between these objects.

#### Relationships between objects:
Association: A and B can call each other.
An association is a solid line between two classes, directed from the source class to the target class. The name of the property goes at the target end of the association, together with its multiplicity.
    - the multiplicity of a property is an indication of how many objects may fill the propery. Lower bound and an upper bound are usually defined but not always.
    - Type A: 1 (an order must have precisely one customer.)
    - Type B: 0..1 (A corporate customer may or may not have a single sales rep.)
    - Type C: * (A customer need not place an Order, and there is no upper limit to the number of Orders a Customer may place-zero or more orders.)

Inheritance: A inherits from B. A "is-a" B.
Inheritance is the concept of acquiring the resource from parents or base class by the child class.
In inheritance, the class which allows its properties to be shared is known as the parent class and the class which aquires the properties from its parent class is known as the child class.
Inhertitance greatly reduces the need to code again and allows code resuability.

Composition: A "has-an" instance of B. B cannot exist without A.
Aggreagation: A "has-an" instance of B. B can exist without A.

Abstract class:
 - An abstract class is a particular type of class that cannot be instantiated.
 - An abstract class is degined to be inherited by subclasses that implement or override its methods.
 - In other words, abstract classes are either partially implemented or not implemented at all.
 - You can have functionality in your abstract class-the methods in an abstract class can be both abstract or concrete.
 - You can take advantage of abstract classes to design components and specify some level of standard functionality that must be implemented by derived classes.
 


