# Debra Event Management System

## Project Overview
The **Debra Event Management System** is a scalable and maintainable solution designed to streamline event management. Built using a Service-Oriented Architecture (SOA), it enables efficient management of events, ticketing, sales, and partner integrations. This system is developed as part of the High National Diploma in Computing and Software Engineering program.

## Table of Contents
- [Project Overview](#project-overview)
- [Architecture](#architecture)
- [Features](#features)
- [System Design](#system-design)
- [Deployment](#deployment)
- [Testing](#testing)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)

---

## Architecture
The system is based on **Service-Oriented Architecture (SOA)**, allowing modular and independent services for each core functionality. It also includes elements of microservices, making the application highly flexible and adaptable.

### Key Architectural Components
- **Event Service**: Manages event creation, updates, and deletion.
- **Ticket Service**: Handles ticket availability, pricing, and sales.
- **Sales Service**: Tracks transactions and records for event tickets.
- **Partner Service**: Manages external partners for ticket sales and promotions.
- **Customer Service**: Stores and manages customer data.

Each component is a standalone service with a REST API for CRUD operations, facilitating integration with other applications.

## Features
1. **Event Management**: Create, update, and manage events.
2. **Ticket Sales**: Issue and manage tickets for events.
3. **Partner Integration**: Collaborate with external partners for ticket distribution.
4. **Sales Tracking**: Monitor ticket sales and revenue data.
5. **Customer Management**: Manage profiles of event attendees and partners.

## System Design
The design includes class, use case, and entity relationship diagrams to illustrate system relationships and data flow. These diagrams depict how different system components interact within the SOA framework, ensuring a cohesive yet modular design.

## Deployment
The application supports several deployment options, including:
- **Server-Based Deployment**: Suitable for smaller, single-server setups.
- **Docker**: Each service is containerized for consistency and portability.
- **Kubernetes**: Manages the deployment, scaling, and maintenance of containers, ensuring scalability and fault tolerance.

## Testing
The project underwent rigorous testing to ensure functionality, performance, and security:
- **API Testing**: Verifies that each endpoint performs its intended operations.
- **Functional Testing**: Validates individual services and CRUD functionalities.
- **Performance Testing**: Assesses system responsiveness under various loads.
- **Security Testing**: Checks for vulnerabilities and unauthorized access.

### Test Coverage
Test cases are provided for each service component, including scenarios for API endpoints, error handling, and data consistency.

## Technologies Used
- **Programming Languages**: C, C++, Java, JavaScript
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: RESTful APIs
- **Database**: MySQL, Microsoft SQL Server, Oracle
- **Deployment Tools**: Docker, Kubernetes
- **Design Tools**: Figma, Adobe Photoshop

## Getting Started
1. **Clone the Repository**: Clone the repository to your local machine.
2. **Setup Environment**: Install Docker and Kubernetes (if applicable).
3. **Run Containers**: Use Docker to build and run each service container.
4. **Access the Application**: Once deployed, access the application via the specified endpoints.

## Contact
For any questions or collaboration opportunities, please reach out via email: [nawodsandakalum.lk@gmail.com](mailto:nawodsandakalum.lk@gmail.com)
