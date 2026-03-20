 Overview of the Code

This snippet demonstrates a CQRS-based command handler integrated with an event-driven architecture using RabbitMQ, built with .NET + MediatR.

 What it does:
Handles a CreateOrderCommand
Persists order data using a repository pattern
Publishes an OrderCreatedEvent to a message broker (RabbitMQ)
Ensures separation of concerns (write vs event dispatch)
 Why this is non-trivial

This code reflects mid-level engineering capability because it:

Implements CQRS (Command Query Responsibility Segregation)
Uses MediatR pipeline for clean request handling
Integrates RabbitMQ messaging for asynchronous processing
Applies Dependency Injection + Repository Pattern
Handles async operations and failure safety
Why I chose this example

I chose this snippet because it demonstrates:

Real-world backend architecture used in scalable systems
My ability to design loosely coupled microservices
Understanding of distributed systems patterns
Clean, maintainable, and testable code structure
