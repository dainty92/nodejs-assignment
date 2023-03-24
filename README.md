<!-- QUESTION 1:    Define Monolithic architecture -->
Monolithic architecture refers to a traditional software design approach where an application is developed as a single, cohesive unit. In this architecture, all the application's components are tightly integrated and interconnected, with the application's functionality and data tightly coupled within the same codebase.
In a monolithic architecture, the application typically runs on a single server, with all the application's layers (such as presentation, business logic, and data access) running in the same process, sharing the same resources. This approach can make it easier to develop and deploy applications, as there is no need to manage different components separately.
However, monolithic architectures can also make it more challenging to maintain and scale applications, as changes to one component can affect the entire system, and scaling requires scaling the entire application rather than just specific components.


<!-- QUESTION 2:    Explain microservices in your own understanding -->
Microservices is a modern approach to software development where an application is built as a collection of small, independent, and loosely coupled services that communicate with each other through APIs. Each microservice is responsible for a specific, well-defined business capability or function, and can be developed, deployed, and scaled independently of the other microservices.


<!-- QUESTION 3:    Which of the backend architecture appeals to you and why? -->
The choice of backend architecture will depend on the specific needs and requirements of the application. A monolithic architecture will be more suitable for smaller, less complex applications that require a straightforward development and deployment process. This makes it easier to develop, test, and deploy, as all components of the application are in one codebase and can be managed together. It may also be easier to ensure consistency and maintainability of the codebase.


<!-- QUESTION 4:    Is Nodejs a multithreaded language? -->
Node.js is a single-threaded language. However, it does support asynchronous and non-blocking I/O operations, which can enable it to handle multiple requests concurrently without blocking the execution of other operations. It execute tasks in parallel using techniques such as asynchronous I/O and worker threads.

<!-- QUESTION 5:    What does REPL stand for? -->
REPL stands for "Read-Evaluate-Print Loop".