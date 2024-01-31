# Design-Pattern 💻
![](https://private-user-images.githubusercontent.com/65750784/301087556-9321edfc-7bda-434d-ab5b-05cdd9029ac4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY2ODk2NjQsIm5iZiI6MTcwNjY4OTM2NCwicGF0aCI6Ii82NTc1MDc4NC8zMDEwODc1NTYtOTMyMWVkZmMtN2JkYS00MzRkLWFiNWItMDVjZGQ5MDI5YWM0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTMxVDA4MjI0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTI2MzM5NjczOTBlNmM5OGYyMGUwOWYwMTAzMmM2NDg0YjVkY2YwNWU1Y2IyMzcwOGQ4MzBkYTIwMjBlMGQ0YzImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.aGk7h4ljqPLrGZu7_2Tn4tBVNvK_-9GyFYPsq5EGEgU)  
Design patterns are the well proved solution of commonly occuring problems in software design.
A design pattern is a general reusable solution to a commonly occurring problem in software design. It is a proven approach that provides a template or guideline for solving a specific design problem while promoting good software design practices such as modularity, reusability, and maintainability.  Design patterns capture best practices and design principles that have been developed and refined by experienced software developers over time. They represent solutions to recurring problems and provide a common vocabulary for developers to communicate and share their design ideas.

### Design patterns can be classified into three main categories: 🟠
![](https://private-user-images.githubusercontent.com/65750784/301087683-d91d73ed-1ba6-427b-9a91-250568ad3c35.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY2ODk2NjQsIm5iZiI6MTcwNjY4OTM2NCwicGF0aCI6Ii82NTc1MDc4NC8zMDEwODc2ODMtZDkxZDczZWQtMWJhNi00MjdiLTlhOTEtMjUwNTY4YWQzYzM1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTMxVDA4MjI0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTVlMTYzYzMyZTg2MGM2ZGY3YzRmODA5MWE2NGRlMWI3M2M0ZjY2YzQwYWZkYzNjMzYyY2Q3NzQyMzgyMmQ1OWEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.eIYlwMBwehJ5BAUxvwkD5m_xDrXcbdqYx6DRemXGNuk)

1. ***Creational Patterns:*** 📘
These patterns deal with object creation mechanisms, providing ways to create objects in a manner that is flexible, decoupled from the specific classes, and suitable for the situation. Examples of creational patterns include the Singleton, Factory Method, and Builder patterns.
2. ***Structural Patterns:*** 📘
These patterns focus on the composition of classes and objects to form larger structures, providing ways to organize classes and objects to achieve flexibility, extensibility, and maintainability. Examples of structural patterns include the Adapter, Decorator, and Composite patterns.  
3. ***Behavioral Patterns:*** 📘
These patterns address the interaction and communication between objects, providing ways to define the responsibilities and collaborations among objects to achieve loose coupling and flexibility. Examples of behavioral patterns include the Observer, Strategy, and Command patterns.

>[!note]
>Design patterns are not specific to a particular programming language or technology. They are higher-level concepts that can be implemented in various languages and frameworks. By utilizing design patterns, developers can create more robust, modular, and maintainable software systems.Design patterns include creational patterns, which deal with object creation. structural patterns, which focus on object composition and organization. and behavioral patterns, which deal with the communication between objects and classes.

## Creational Pattern : 💻
Creational design patterns provide various object creation mechanisms, which increase flexibility and reuse of existing code.  
[Read](https://medium.com/@saygiligozde/design-patterns-in-java-5251032ca244)
### 1. **Singleton Method :** 📘
![](https://private-user-images.githubusercontent.com/65750784/301103120-2982aba5-a0a2-47f8-8caf-ec9f0e14a997.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY2OTI1MTAsIm5iZiI6MTcwNjY5MjIxMCwicGF0aCI6Ii82NTc1MDc4NC8zMDExMDMxMjAtMjk4MmFiYTUtYTBhMi00N2Y4LThjYWYtZWM5ZjBlMTRhOTk3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTMxVDA5MTAxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWFlY2I1YzY2MDc0ZGQ1MGI1YjVhOGJkMTMxMDZiZDY3ZjE2M2ZmYWFmMjIyMjgwODJkN2M2M2U4ZjI3ZjRlM2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.uBvKoTl9itWMFw732mtTUJt0Ts2_6NaamvJqXVf3M3Y)  

Singleton is a creational design pattern that lets you ensure that a class has only one instance, while providing a global access point to this instance.  
[Read the_blog](https://refactoring.guru/design-patterns/singleton).

Singleton works on the concept of one and only one instance of the object, which results in the global control of a resource. In simple words, the Singleton design pattern ensures that only one instance of the class will be created and that instance will have global access within the application.
When you want to ensure that only one instance of a class exists, for example, a single database object shared by different parts of the program, you should use the Singleton design pattern.
![](https://private-user-images.githubusercontent.com/65750784/301108443-360265fa-9070-4078-ae66-af5cec32e9af.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY2OTM1ODYsIm5iZiI6MTcwNjY5MzI4NiwicGF0aCI6Ii82NTc1MDc4NC8zMDExMDg0NDMtMzYwMjY1ZmEtOTA3MC00MDc4LWFlNjYtYWY1Y2VjMzJlOWFmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTMxVDA5MjgwNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTM0MjgzOWNiZGE2ZWRjZmFiODA4ZTg5OTRiNmZlZTllNWU4Yzk2MDQxMjllMTM0MTc3MTAzMDY4NjJlODcyNjgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.-CvWta-net7ZWria2Ev8PViKZKlybA6ZmzUc3y_C0EE)
- [x] ***Real-World Analogy:*** 🟠  
The government is an excellent example of the Singleton pattern. A country can have only one official government. Regardless of the personal identities of the individuals who form governments, the title, “The Government of X”, is a global point of access that identifies the group of people in charge.
#### **How to Implement:** 🔶  
- Add a private static field to the class for storing the singleton instance.
- Declare a public static creation method for getting the singleton instance.
- Implement “lazy initialization” inside the static method. It should create a new object on its first call and put it into the static field. The method should always return that instance on all subsequent calls.
- Make the constructor of the class private. The static method of the class will still be able to call the constructor, but not the other objects.
- Go over the client code and replace all direct calls to the singleton’s constructor with calls to its static creation method.

#### **Pros and Cons:** 🟠
- [x] You can be sure that a class has only a single instance.
- [x] You gain a global access point to that instance.
- [x] The singleton object is initialized only when it’s requested for the first time.

- [ ] Violates the Single Responsibility Principle. The pattern solves two problems at the time.
- [ ] The Singleton pattern can mask bad design, for instance, when the components of the program know too much about each other.
- [ ] The pattern requires special treatment in a multithreaded environment so that multiple threads won’t create a singleton object several times.
- [ ] It may be difficult to unit test the client code of the Singleton because many test frameworks rely on inheritance when producing mock objects. Since the constructor of the singleton class is private and overriding static methods is impossible in most languages, you will need to think of a creative way to mock the singleton. Or just don’t write the tests. Or don’t use the Singleton pattern.

### **2. Factory Method:** 📘
Factory Method is a creational design pattern that provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created.The Factory Method is a creational design pattern that provides a solution to create product objects without the need to specify their concrete classes during the creation process.
The Factory Method is used to conserve system resources by reusing existing objects instead of reconstructing them repeatedly.  
[Read the blog](https://refactoring.guru/design-patterns/factory-method).  
![](https://private-user-images.githubusercontent.com/65750784/301113096-6653cad6-598f-42b5-88b0-aa91eff30079.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY2OTQ0NTUsIm5iZiI6MTcwNjY5NDE1NSwicGF0aCI6Ii82NTc1MDc4NC8zMDExMTMwOTYtNjY1M2NhZDYtNTk4Zi00MmI1LTg4YjAtYWE5MWVmZjMwMDc5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTMxVDA5NDIzNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBhZGY4NzUyNDYzZDY3NWI5YmI0NjhiNGU5YzExMzRiYTdhZjAxN2FkMTJhNmE2ZTIxZjIxYmVkNzdlNDY5YjMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.G7BJF7jK1Y0MWPRcw12efnW2ydwTu6t-V3Z3OhSLad0)  
#### **Pros and Cons:** 🟠  
- [x] You avoid tight coupling between the creator and the concrete products.
- [x] Single Responsibility Principle. You can move the product creation code into one place in the program, making the code easier to support.
- [x] Open/Closed Principle. You can introduce new types of products into the program without breaking existing client code.
- [ ] The code may become more complicated since you need to introduce a lot of new subclasses to implement the pattern. The best case scenario is when you’re introducing the pattern into an existing hierarchy of creator classes.

### **3. Abstract Factory:** 📘  
Abstract Factory is a creational design pattern that lets you produce families of related objects without specifying their concrete classes.  
[Read the article](https://refactoring.guru/design-patterns/abstract-factory).  

![](https://private-user-images.githubusercontent.com/65750784/301117523-184d391a-8a78-4480-9b2a-8273c061869e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY2OTUzMDUsIm5iZiI6MTcwNjY5NTAwNSwicGF0aCI6Ii82NTc1MDc4NC8zMDExMTc1MjMtMTg0ZDM5MWEtOGE3OC00NDgwLTliMmEtODI3M2MwNjE4NjllLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTMxVDA5NTY0NVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWNhNzY5ZjJkOGRhYzkzZGQyZmVkMjNhYzI4NzAzZjZlMWI0OWRlZmM3NDU5MGM1ZDY0ZDg1MTA3OWQwMGY1MjcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.W8YnIfGQx2b-U2OwRN96i34hN-aotNIa8c_42TDvCoo) 

#### **Advantages:** 🟠  
- Reduces the number of parameters in the constructor and provides readable method calls.
- Allows object instantiation in a complete state.
- Simplifies the building process of immutable objects.
#### **Disadvantages:** 🟠  
- It increases the number of lines of code but offers design flexibility and improved code readability.
- Requires creating separate ConcreteBuilder classes for each product type.







