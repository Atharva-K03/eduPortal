# **EduPortal**
EduPortal is a multi-module microservices project designed to handle various functionalities for different roles and features. Each microservice is responsible for a specific domain, ensuring scalability, independence, and maintainability.
## **Basic Microservices and Their Functions**
1. **Student Service (`student-service`)**:
    - Handles all operations related to students.
    - Basic functionality includes:
        - Adding a new student.
        - Fetching student details by ID.
        - Updating student information.
        - Deleting a student's record.

2. **Teacher Service (`teacher-service`)**:
    - Manages teacher-specific operations.
    - Basic functionality includes:
        - Adding new teachers.
        - Fetching teacher details by ID.
        - Updating teacher information.
        - Removing teacher records.

3. **Security Service (`security-service`)**:
    - Handles authentication, authorization, and security for the entire application.
    - Basic functionality includes:
        - User login with JWT generation.
        - User registration.
        - Token validation.
        - Role-based access control.

4. **Discovery Server (`discovery-server`)**:
    - Acts as a service registry using Eureka.
    - Basic functionality includes:
        - Registering all microservices.
        - Enabling services to discover and communicate with each other.
        - Load balancing and fault-tolerance.

5. **API Gateway (`api-gateway`)**:
    - Serves as a centralized entry point to route requests to the appropriate microservices.
    - Basic functionality includes:
        - Routing requests to Student, Teacher, and Security services.
        - Centralized request filtering and handling.
        - Implementing cross-cutting concerns like authentication and logging.

## **Clone the Repository**
To get started, follow these steps:
1. Open your terminal or command prompt.
2. Clone the repository using the following command:
``` bash
   git clone https://github.com/Atharva-K03/eduPortal.git
```
1. Navigate into the project directory:
``` bash
   cd eduPortal
```
You are now ready to explore and work on the project!
