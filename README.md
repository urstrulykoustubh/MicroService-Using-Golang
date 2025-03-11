# MicroService-Using-Golang

In this project, I explored the microservices architecture, which involves breaking down a larger application into smaller, self-contained services that can work together. I learned how microservices can make an application more scalable, maintainable, and easier to deploy. Key characteristics of a microservice include:

Easy to maintain and test.
Loosely coupled with other parts of the system.
Can be deployed independently.
Organized around specific business functions.
Often owned and maintained by a small, focused team.
What I’ve Built

Throughout this project, I developed several microservices that communicate with each other to form a distributed application. These services include:

Front End Service: A web service that displays user-facing pages.
Authentication Service: Manages user authentication, backed by a Postgres database.
Logging Service: Logs events and stores them in a MongoDB database.
Listener Service: Listens for messages from RabbitMQ and processes them.
Broker Service: (Optional) Acts as a single entry point to route requests to the correct service.
Mail Service: Accepts a JSON payload, formats it as an email, and sends it out.
Technologies Used
I developed all the services using Go (Golang), a language well-suited for building distributed applications due to its simplicity and performance. For deploying and managing the services, I utilized Docker Swarm and Kubernetes. These tools helped with scaling, updating, and maintaining the application with minimal downtime.

What I’ve Learned
By the end of this project, I gained practical experience in:

Understanding the microservices architecture and when it’s the right approach.
Developing loosely coupled, single-purpose services that communicate with each other in a distributed system.
Implementing communication between services using REST APIs, RPC, and gRPC.
Using RabbitMQ and AMQP to push events between services.
Deploying and managing a distributed application using Docker Swarm and Kubernetes, allowing for easy scaling and updates.
