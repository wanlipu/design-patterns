# Design Patterns


## Books
- Design Patterns: Elements of Reusable Object-Oriented Software
  - https://github.com/BartVandewoestyne/Design-Patterns-GoF
  - What Is MVC? Simple Explanation
    - https://www.youtube.com/watch?v=pCvZtjoRq1I
- Head First Design Patterns: A Brain-Friendly Guide
  - https://www.amazon.com/dp/0596007124//ref=cm_sw_su_dp?tag=nethta-20
  - https://www.youtube.com/watch?v=vNHpsC5ng_E&list=PLF206E906175C7E07


## Microsoft Tutorial
- SOLID Design Patterns (start from here):   https://www.youtube.com/watch?v=agkWYPUcLpg
- Design Patterns: Command/Memento:   https://www.youtube.com/watch?v=zRbHlDeon3E
- Design Patterns: Strategy:   https://www.youtube.com/watch?v=QZIvlny1Onk
- Design Patterns: Template Method:   https://www.youtube.com/watch?v=MfAvs0n9uMs
- Design Patterns: Observer and Publish-Subscribe:   https://www.youtube.com/watch?v=72bdaDl4KLM
- Design Patterns: Singleton:   https://www.youtube.com/watch?v=sbML3xFHRbI
  - Use Cases:
    - There are many objects we only need one of: thread pools, caches, dialog boxes, objects that handle preferences and registry settings, objects used for logging, and objects that act as device drivers to devices like printers and graphics cards. In fact, for many of these types of objects, if we were to instantiate more than one we'd run into all sorts of problems like incorrect program behavoir, overuse of resources, or inconsistent results. 
  - In many ways, the Singleton Pattern is a convention for ensuring one and only one object is instantiated for a given class. If you've got a better one, the world would like to hear about it; but remember, like all patterns, the Singleton Pattern is a time-tested method for ensuring only one object gets created. The Singleton Pattern also gives us a global point of access, just like a global variable, but without the downsides. 
    - Downsides of global variables: for example, if you assign an object to a global variable, then that object might be created when your application begins. Right? What if this object is resource intensive and your application never ends up using it? As you will see, with the Singleton Pattern, we can create our objects only when they are needed. 
- Design Patterns: Factories:   https://www.youtube.com/watch?v=JEk7B_GUErc
  - Factory Method Pattern
    - The Factory Method Pattern defines an interface for creating an object, but lets subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.
  - Abstract Factory Pattern 
    - The Abstract Factory Pattern provides an interface for creating families of related or dependent objects without specifying their concrete classes. 
  - Factory vs Abstract Factory: https://stackoverflow.com/questions/5739611/what-are-the-differences-between-abstract-factory-and-factory-design-patterns
- Design Patterns: Adapter and Façade:   https://www.youtube.com/watch?v=XYa0rmRMZ1Q
- Design Patterns: Decorator:   https://www.youtube.com/watch?v=6PPMR0GWrZQ
