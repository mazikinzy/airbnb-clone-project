# airbnb-clone-project
A booking platform project


# Team Roles
## Backend Developer
A backend developer plays a crucial role in a project by building and maintaining the server-side infrastructure that powers the application.
## Database Administrator
Responsible for the performance, integrity, and security of the project’s database
## DevOps Engineer
Set up and manage continuous integration and continuous delivery systems to automate testing and deployment of the project.
## QA Engineer
Ensures that software products are reliable, bug-free, and meet user expectations before they’re released.

# Technology Stack
### **Django**
A high-level Python web framework used for building the RESTful API.
### **Django REST Framework**
Provides tools for creating and managing RESTful APIs.
### **PostgreSQL**
A powerful relational database used for data storage.
### **GraphQL**
Allows for flexible and efficient querying of data.
### **Celery**
For handling asynchronous tasks such as sending notifications or processing payments.  
### **Redis**
Used for caching and session management.
### **Docker**
Containerization tool for consistent development and deployment environments.
### **CI/CD Pipelines**
Automated pipelines for testing and deploying code changes.

# Database Design
### **Users**
### **Properties**
### **Bookings**
### **Reviews**
### **Payments**

# Feature Breakdown
### **API Documentation**
**OpenAPI Standard**  
OpenAPIStandard is a widely adopted specification for describing RESTful APIs in a machine-readable format using JSON or YAML. It defines the structure of an API — including endpoints, request/response formats, authentication, and error handling so that both humans and software tools can understand and interact with the API without needing access to the source code.
In this booking system project, OpenAPI Standard will play a crucial role in streamlining the development, improved testing and seamless integration of this project.

**Django REST Framework**  
Django REST Framework is a powerful and flexible toolkit built on top of Django for creating Web APIs. It simplifies the process of building RESTful services by providing:  
**Serialization:** *Converts complex data types (like Django models) into JSON and vice versa.*  
**Authentication & Permissions:** *Built-in support for token-based auth, OAuth, and custom permission classes.*  
**Browsable API:** *A web interface for testing and interacting with your API.*  
**Generic Views & ViewSets:** *Prebuilt logic for common CRUD operations.*  
**Validation:** *Automatic input validation through serializers.*
