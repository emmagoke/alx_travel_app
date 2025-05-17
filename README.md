# ALX Travel App

## About the Project

The `alxtravelapp` project is a real-world Django application that serves as the foundation for a travel listing platform. This initial milestone focuses on setting up a robust project structure, configuring a scalable MySQL database, and integrating essential tools like Swagger for API documentation and `django-environ` for maintainable configurations. The primary aim is to equip learners with industry-standard best practices for initiating and managing Django-based projects efficiently.

This milestone will guide you through setting up a scalable backend, integrating MySQL for database management, and leveraging Swagger (via `drf-yasg`) for automated API documentation. These foundational steps are critical in preparing the application for future feature development and enabling seamless team collaboration.

## Learning Objectives

As a professional developer, successfully completing this milestone will enable you to:

- **Master Advanced Project Initialization:**
  - Learn to bootstrap Django projects with modular, production-ready configurations.
  - Employ environment variable management for secure and scalable application settings.
- **Integrate Key Developer Tools:**
  - Set up and effectively use Swagger (via `drf-yasg`) for comprehensive API documentation.
  - Implement CORS (Cross-Origin Resource Sharing) headers and configure MySQL for robust API interactions and data management.
- **Collaborate Effectively Using Git:**
  - Structure your projects in a way that facilitates team collaboration through a version-controlled setup.
- **Adopt Industry Best Practices:**
  - Follow established best practices in managing project dependencies, database configurations, and overall application structure.

## Requirements

To successfully complete this milestone, ensure you meet the following prerequisites:

- Familiarity with Django and Django REST Framework.
- Knowledge of MySQL and fundamental database management concepts.
- Understanding of version control principles and practical usage of Git.
- A basic grasp of environment variable management, specifically using `django-environ`.

## Key Highlights

### 1. Project Initialization:

- Create a new Django project named `alxtravelapp`.
- Add a Django app named `listings` to encapsulate the core functionalities related to travel listings.

### 2. Dependency Management:

Install the following essential Python packages:

- **`django`**: The core framework for web application development.
- **`djangorestframework`**: The toolkit for building robust REST APIs.
- **`django-cors-headers`**: For setting up Cross-Origin Resource Sharing to allow or restrict web browser requests from different domains.
- **`drf-yasg`**: A Swagger/OpenAPI generation tool for Django REST Framework.
- **`celery`**: (For future implementation) An asynchronous task queue/job queue based on distributed message passing.
- **`rabbitmq`**: (For future implementation) A message broker that Celery can use.
- **`mysqlclient`**: (Or an alternative like `PyMySQL`) A MySQL database adapter for Python.
- **`django-environ`**: For managing environment variables.

You can install these using pip:

```bash
pip install django djangorestframework django-cors-headers drf-yasg celery mysqlclient django-environ
```
