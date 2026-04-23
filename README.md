This project demonstrates the deployment of a production-ready three-tier web application on Amazon Elastic Kubernetes Service using Amazon Web Services. The architecture follows a microservices-based approach, separating the application into presentation, application, and database layers for better scalability, maintainability, and performance.

The application is containerized using Docker and deployed on a Kubernetes cluster managed by EKS. The frontend layer handles user interactions, while the backend services process business logic and communicate with the database layer for persistent storage. Kubernetes resources such as Deployments, Services, and Ingress are used to manage application lifecycle, networking, and traffic routing.

An Application Load Balancer is integrated to distribute incoming traffic efficiently across multiple pods, ensuring high availability and fault tolerance. Auto-scaling capabilities are enabled to dynamically adjust resources based on traffic demand, improving performance and cost efficiency.

The infrastructure is deployed within a secure VPC, ensuring network isolation and controlled communication between components. Best practices such as rolling updates, self-healing, and declarative configuration are implemented to maintain reliability and minimize downtime.

This project highlights real-world DevOps and cloud-native practices, including containerization, orchestration, and scalable deployment strategies. It serves as a practical example for deploying modern applications on Kubernetes using AWS managed services.
