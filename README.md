# AirBnB Clone Project

Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security.

## Technology Stack

- **Django**: A high-level Python web framework used for building the RESTful API.
- **Django REST Framework**: Provides tools for creating and managing RESTful APIs.
- **PostgreSQL**: A powerful relational database used for data storage.
- **GraphQL**: Allows for flexible and efficient querying of data.
- **Celery**: For handling asynchronous tasks such as sending notifications or processing payments.
- **Redis**: Used for caching and session management.
- **Docker**: Containerization tool for consistent development and deployment environments.
- **CI/CD Pipelines**: Automated pipelines for testing and deploying code changes.


## Team Roles

- **Backend Developer**: Responsible for implementing API endpoints, database schemas, and business logic.
- **Database Administrator**: Manages database design, indexing, and optimizations.
- **DevOps Engineer**: Handles deployment, monitoring, and scaling of the backend services.
- **QA Engineer**: Ensures the backend functionalities are thoroughly tested and meet quality standards.


## Database Design

- Users: A user can have multiple properties, a booking belongs to a property
- Properties: A property can have multiple Booking, Reviews and Payments
- Bookings: Booking are made on different Properties
- Reviews: Reviews are made for each booking
- Payments: Payments are made on booking


## Feature Breakdown

- **User Management**: Registering a new user, and managing there profiles
- **Property Management**: Creating a new property, managing and deleting properties
- **Booking System**: Make booking, manage booking (like check in and out details)
- **Payment Processing**: Handles payments related to a bookings
- **Review System**: Create review post, manage for each properties


## API Security

Security is a crtical part of AirBnB, Client application would have have to be authenticaled and if not would not be authorized to consume the api facing backend to create booking, review and manage users, also ratelimiting is also a means of reducing abuse by authorized client consuming the API backend


## CI/CD Pipeline

The following tools would be used for setting up automated development and testing:
- GitHub Actions
- Docker