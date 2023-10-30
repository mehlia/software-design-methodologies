# SOFTWARE DESIGN METHODOLOGIES RESEARCH

## STRUCTURED DESIGN:
  Structured design in software engineering refers to a methodical & organised approach to developing software systems. It involves breaking down the system into smaller, more manageable parts, each with its specific function, purpose and defined interactions. The primary objective of structured design is to create a clear and understandable architeture for the software system.

## FUNCTION-ORIENTED DESIGN:
  Function-oriented design in software engineering is an approach that focuses on designing software based on decomposing the system's functionality into smaller, more manageable functions or procedures. This design methodology emphasises the creation and organinisation of functions that performs specific tasks within the software system.

## OBJECT-ORIENTED DESIGN (OOD):
  Object-oriented design in software engineering is a methodology for designing computer programs using the concept of "objects". It revolves around creating software systems by defining objects that have data fields (attributes) and associated procedures (methods or functions) to operate on that data. Objects can interact with one another to achieve the desired functionalities and behaviours within the system.

## QUESTIONS

### 1. What do we mean by coupling and cohesion when discussing structured design?
  **Coupling** relates to the degree of dependency between different modules or components within a system. It measures how much one module relies on or is connected to another.
  - **Low Coupling** = ideally, modules should have low coupling. Low coupling means that modules are relatively independent and have minimal reliance on each other. Changes in one module have a limited impact on other modules, allowing for easier maintenance and modifications.
  - **High Coupling** = high coupling implies strong interdependence between modules. A change in one module might necessitate changes in multiple other modules, making the system less flexible and more challenging to maintain or evolve.
  
  **Cohesion** refers to the degree to which elements within a module or component belong together. It assesses how strongly the elements within a module are related to each other and work towads a common purpose.
  - **High Cohesion** = high cohesion implies that the elements within a module are highly related, focused on a single task or purpose. A highly cohesive module concentrates on a specific and well-defined set of responsibilities, making the module more understandable and maintainable.
  - **Low Cohesion** = low cohesion occurs when the elements within a module are less related or perform multiple disparate tasks. Low cohesion can result in a lack of clarity and increased complexity, making it harder to maintain and comprehend the module's functionality.

  In structured design, the objective is to have high cohesion and low coupling. This means modules should be highly cohesive internally, focusing on a single, well-defined task, while being loosely coupled to other modules, minimising interdependencies. High cohesion and low coupling results in more manageable, maintainable and scalable software systems, also enhancing the system's flexibility.

### 2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?
  **Top-Down Design** is an approach that starts with a broader, more abstract view of the system and progressively breaks it down into smaller, more manageable components or modules. It begins with the overall system architecture and then is decomposed into smaller subsystems, modules and eventually individual functions or procedures. This approach allows for heirarchical structure, where each subsequent level represents more detailed functionalities.

  **Bottom-Up Design** is an approach that starts from the smallest components or modules and gradually builds up to create larger systems. It begins with smaller, more specific functionalities or modules and then integrates these smaller components into larger and more comprehensive subsystems or the complete system. This method focuses on building individual pieces first and then assembling them to form larger structures.

  Function-oriented design aligns more with bottom-up design because it emphasises the creation and organisation of functions or procedures that perform specific tasks within the system.

### 3. In which design methodology would a class diagram be most useful?
  UML/Class diagrams are most useful in methodologies that emphasize object-oriented design. This is because the diagrams provide a visualisation of object structures, definition of object relationships and designing object-oriented systems. 
   
### 4. What are the four pillars of object oriented programming? Give a single-sentence description of each.
  1. **Encapsulation** =  the bundling of data and the methods that operate on that data into a single unit, protecting the data from outside interference and misuse.
  2. **Abstraction** = involves hiding the compleximplememntation details and displaying only the necessary features of an object, allowing the user to interact with it without needing to understand its inner workings.
  3. **Inheritance** = the mechanism that allows a class to inherit properties and behaviour from another class, enabling the creation of a heirarchy and the reusability of code.
  4. **Polymorphism** = allows objects of different classes to be treated as objects of a common superclass, permitting different classes to be used interchangeably through a shared interface, providing flexibility in the use of objects.
   
### 5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?
  The strategy pattern is a behavioural design pattern that enables defining a family of algorithms, encapsulating each one and making them interchangeable. It allows the algorithm to vary independently of the clients that use it.

  In OOD, the strategy pattern involves creating a set of algorithms as separate classes, defining a common interface for these algorithms and allowing the context (client) to choose and use an algorithm by referencing it through the common interface. The client can switch between different strategies without changing its code, promoting flexibility and maintainability.

  In a functional system, the strategy pattern can be implemented through higher-order functions or function composition. Instead of using different classes for each strategy, functions that represent different strategies are created. These functions can be passed as arguments or composed with other functions. This allows the behaviour to be determined at runtime by passing the appropriate function or by composing functions in different ways.

  Key difference: OOD systems use classes and interfaces to encapsulate algorithms while functional systems tend to use functions as first-class citizens to achieve the same goal, relying on higher-order functions and function composition for strategy interchangeability.
   
### 6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
  A suitable methodology would be the Agile methodology:
   1. **Iterative Development** = Agile methodology focuses on iterative development, allowing for continuous improvement and adaptation. This approach enables quick adjustments based on feedback and evolving market needs. For a paymentt system that should cater to various sectors, this adaptability is crucial.
   
   2. **User-Centric Design** = Agile emphasises user involvement throughout the development process. This ensures that the payment system is designed to be user-friendly, accommodating different customer needs and preferences across sectors. Understanding the unique requirements of various industries and user groups will be crucial for widespread adoption.
   
   3. **Flexibility & Responsiveness** = the Agile approach allows for flexibility in responding to changing market trends, regulations and technological advancements. This adaptability is essential in an ever-evolving digital payment landscape, ensuring the system remains relevant and compliant across different sectors.
   
   4. **Continuous Testing & Improvement** = Agile methodology encourages continuous testing, which is vital for a payment system to guarantee security and reliability. It allows for frequent updates and improvements based on real-time testing and feedback, reducing the risk of vulnerabilities.
   
   5. **Cross-Functional Collaboration** = Agile promotes cross-functional collaboration among teams. This is particularly beneficial for a payment system that needs to work seamlessly across various sectors. Collaboration among different expertise areas such as finance, technology, security and customer service is crucial for a well-rounded solution.
   
   6. **Scalability & Sustainability** = Agile supports scalability, which is vital for a payment system aiming for maximum market share. The system should be designed to accommodate increased demand and usage without sacrificing performance or security.
   