https://dokumen.pub/practical-object-oriented-design-an-agile-primer-using-ruby-secondnbsped-0134456475-9780134456478.html


Chapter 1.1

An object oriented application is composed of a number of small objects that talk with each other to achieve a working system.

When objects talk to each other they do it through messages.
- In order to send these messages, the sender needs info on the receiver
- This "info" creates dependencies between those two
- These dependencies resist change

Object Oriented design is not about removing dependencies

There is not a system in this world where in the parts do not communicate with each other.
There is not a system that has parts without having to depend on each other.

Object Oriented design gives us the techniques to: 
- manage these dependencies,
- or to design a system,
- or to neatly arrange a system of parts in a way that allows for "change"

When dependencies are **unmanaged**, changing one part/object means that there will also be changes to its dependents, a ripple effect on a chained number of dependencies

Design that anticipate future features are garbagio. Instead, good design accepts that changes will happen in the future and it gives us wiggle room for future changes.
### the goal of design is to make the future cost less


1.2

Design is not a one-size-fits-all. It's art and it's a journey of decisions; a flow.

Just like how nature flows: natural order is the principle that governs life, patterns are present in nature. Object oriented design is guided by principles and patterns too.

1.2.1

Five most well known principles of Object Oriented Programming: [[SOLID]].

- S - Single Responsibility
- O - Open/Closed
- L - Liskov Subsitution
- I - Interface Segregation
- D - Dependency Inversion

Other principles: 
- law of demeter
- dry (dont repeat yourself)