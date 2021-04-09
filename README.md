Notes for S.O.L.I.D Principles:
- The reasoning for these principles are to encourage "more maintainable,
understandable, and flexible software." It is important to keep our programs
organized, especially as they become more complex. We want to ensure that not
only is the code comprehensible to ourselves, but others as well.
- Acronym: Solid Responsibility, Open/Closed, Liskov Substitution, Interface
Segregation, Dependency Inversion
- Single responsibility states that "a class should only have one
responsibility," as well as only having "one reason to change."
- Concise classes have fewer test cases, fewer dependencies, and allow for
information to be found much easier.
- Open/Close states that "classes should be open for extension, but closed for
modification."
- By not modifying our classes, we are preventing any further complications
from occuring, as we want to keep its purpose intact.
- Liskov substitution states that if a class is a subtype of another class,
then the subtype can be used as a replacement without any issue to the overall
program.
- Interface segregation states that "larger interfaces should be split into
smaller ones." This will allow for classes that implement the interface to
focus on methods that essential to its functionality.
- Dependency inversions states that both high-level modules and low-level
modules should depend on abstractions. This type of reasoning can be seen when
declaring variables in the constructor, such as by using the this. method,
instead of making a new object.
