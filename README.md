# Flask Microservices Deployment using Docker Compose and Nginx

This project demonstrates a simple production-style microservices architecture using Docker.

The application is built using the Flask framework and is containerized using Docker. Multiple instances of the Flask application are deployed to simulate horizontal scaling and load balancing.

Nginx is used as a reverse proxy and load balancer to distribute incoming HTTP traffic across multiple Flask application containers.

MySQL is used as the backend database with persistent storage configured through Docker volumes. Initial database scripts can be executed automatically during container startup.

Redis is integrated as an in-memory cache layer to improve performance and demonstrate multi-service communication within a Docker network.

Docker Compose is used to orchestrate all services including:

- Multiple Flask application containers
- Nginx reverse proxy
- MySQL database
- Redis cache

This project helps in understanding:

- Containerization using Docker
- Multi-container orchestration using Docker Compose
- Load balancing with Nginx
- Service discovery using Docker internal networking
- Environment variable based configuration
- Persistent storage using Docker volumes
- Basic production-style deployment architecture

To start the application:
