# Service Registry


### Description:

The Service Registry is a central component of a microservices architecture that facilitates service discovery and registration. Built with Spring Cloud Eureka, this service allows microservices to register themselves upon startup and discover other services dynamically.


### Key features include:

- Automatic Service Registration: Microservices can automatically register themselves with the registry when they start.
- Service Discovery: Enables microservices to locate and communicate with each other without hard-coded addresses.
- Load Balancing: Distributes requests across multiple instances of a service for improved performance and reliability.
- Health Monitoring: Continuously monitors the health of registered services, ensuring that only healthy instances receive traffic.