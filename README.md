QuizApp Using Microservices

-This is a basic SpringBoot project developed using microservices for learning purpose.
-I have developed quiz-service and question service project using spring framework. 
-In question-services you can add, update, delete and get questions. In quiz-service you can generate a quiz, give a quiz and get a score.

Microservices :-
Microservices is an architectural style in software development where an application is divided into small, independent services that communicate with each other. Each microservice handles a specific function of the application

Key Component of Microservice that is learn:-
1. Service Registry
A service registry keeps track of all the services and their locations (IP addresses/URLs). Services register themselves to this component, and it helps other services discover and communicate with each other.
Example: Eureka Server (used in the Netflix OSS stack)

2. API Gateway
An API Gateway acts as a single entry point for clients to interact with multiple microservices. It handles routing requests, authentication, and sometimes caching or load balancing.
Example: Zuul or Spring Cloud Gateway

4. Load Balancer
A load balancer distributes incoming network traffic across multiple instances of a service to ensure no single instance gets overwhelmed. This improves availability and reliability.
Example: Ribbon or cloud provider load balancers like AWS ELB

5. Eureka Server (Service Discovery)
Eureka is a service discovery tool that allows microservices to register themselves and discover other services dynamically. It helps locate services based on their names, making communication easier.
Example: Netflix Eureka

6. Feign Client
Feign is a declarative HTTP client used to simplify service-to-service communication. Instead of writing boilerplate HTTP calls, you can use Feign to automatically bind to REST APIs and make requests with ease.
Example: Spring Cloud Feign Client
