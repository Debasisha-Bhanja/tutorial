
S.O.L.I.D is an acronym for the first five object-oriented design(OOD) principles by Robert C. Martin

  Single Responsibility Principle (SRP)
  Open-Closed Principle (OCP)
  Liskov Substitution Principle (LSP)
  Interface Segregation Principle (ISP)
  Dependency Inversion Principle (DIP)
  
  SOLID principles provide a clear pathway for moving from tightly coupled code with poor cohesion and little encapsulation 
  to the desired results of loosely coupled code, operating very cohesively and encapsulating the real needs of the 
  business appropriately.
  
  The Single Responsibility Principle says that classes, modules, etc., should have one and only one reason to change. 
  meaning that a class should have only one job.
  This helps to drive cohesion into a system and can be used as a measure of coupling as well.
  Just because you can add everything you want into your class doesn’t mean that you should. 
  Thinking in term of  responsibilities will help you design your application better. 
  Ask yourself whether the logic you are introducing should live in this class or not. 
  Using layers in your application helps a lot. 
  Split big classes in smaller ones, and avoid *god classes. Last but not least, write straightforward comments.
  *A "God Class" is an object that controls way too many other objects in the system and has grown beyond all logic to become    The Class That Does Everything
  
  The Open-Closed Principle indicates how a system can be extended by modifying the behavior of individual classes or modules,   without having to modify the class or module itself. 
  This simply means that a class should be easily extendable without modifying the class itself.
  This helps you create well-encapsulated, highly cohesive systems.
  You should make all member variables private by default. Write getters and setters only when you need them.
  You should design modules that never change. 
  When requirements change, you extend the behavior of such modules by adding new code, 
  not by changing old code that already  works.

  The Liskov Substitution Principle also helps with encapsulation and cohesion. 
  This principle says that you should not violate the intent or semantics of the abstraction that you are inheriting from 
  or implementing.

  The Interface Segregation Principle helps to make your system easy to understand and use. 
  It says that you should not force a client to depend on an interface (API) that the client does not need. 
  This helps you develop well-encapsulated, cohesive set of parts.

  The Dependency Inversion Principle helps you to understand how to correctly bind your system together. 
  It tells you to have your implementation detail depend on the higher-level policy abstractions, and not the other way around.   This helps you to move toward a system that is coupled correctly, and directly influences that system’s encapsulation 
  and cohesion

These principles, when combined together, make it easy for a programmer to develop software that are easy to maintain and extend. They also make it easy for developers to avoid code smells, easily refactor code, and are also a part of the agile or adaptive software development.
