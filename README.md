# ScooterVolt Microservices

ScooterVolt is a platform for buying and selling second-hand electric scooters, built using a microservices architecture. The platform consists of several independent services, each responsible for a specific aspect of the application.

## Why Microservices?

The decision to use microservices reflects a desire to showcase my knowledge and expertise in this domain, despite the potential for over-engineering. While a less mature version of the project could have been developed as a monolithic application with Domain-Driven Design (DDD), the decision was made to proceed with microservices to demonstrate my proficiency in this area.

By using microservices, we aim to achieve greater flexibility, scalability, and maintainability in the development of ScooterVolt. Each microservice is developed and deployed independently, allowing for faster iterations and more efficient use of resources. This architecture also enables us to easily add or remove functionality as necessary, without impacting the entire application.

## Services

The following microservices are included in the ScooterVolt platform:

- User: This service is responsible for user registration, authentication, and authorization.
- Catalog: This service is responsible for storing, listing, and filtering the ads posted by users.
- Chat: This service is responsible for handling conversations between users who are interested in buying or selling an electric scooter.
- Statistics: This service collects data of interest to the platform, such as the number of registered users, the number of ads posted, the number of sales made, etc.
- Notification: This service is responsible for notifications sent to users about important events on the platform.
- Sales [Future]: This service will handle sales within the platform.
- Shipping [Future]: This service will handle the shipping of electric scooters purchased through the platform.

## Getting Started
To get started with the ScooterVolt platform, please refer to the individual service repositories for setup instructions and documentation. The source code for each microservice can be found in their respective repositories, which are linked below:

- User: [https://github.com/adrigar94/ScooterVolt-User](https://github.com/adrigar94/ScooterVolt-User)
- Catalog: https://github.com/adrigar94/not-yet
- Chat: https://github.com/adrigar94/not-yet
- Statistics: https://github.com/adrigar94/not-yet
- Notification: https://github.com/adrigar94/not-yet
- Sales [Future]: https://github.com/adrigar94/not-yet
- Shipping [Future]: https://github.com/adrigar94/not-yet
