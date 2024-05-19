# project-level-1
Build a lightweight, microservice-based to-do application. The application will have multiple services interacting with each other through REST APIs. The final product will be containerized and deployable on Kubernetes. You'll develop each service in a test-driven way, ensuring code quality and reliability.


Beginner Project: Microservice-based To-Do Application
Project Overview
Build a lightweight, microservice-based to-do application. The application will have multiple services interacting with each other through REST APIs. The final product will be containerized and deployable on Kubernetes. You'll develop each service in a test-driven way, ensuring code quality and reliability.

## Exercise Goals
Learn microservice architecture: Understand how to design, develop, and manage microservices.
Test-driven development (TDD): Write tests before implementing functionality.
Containerization: Learn how to containerize applications using Docker.
API development: Develop REST APIs for inter-service communication.
Incremental development: Break down the project into small, manageable milestones.
Milestones
Set Up Project Repository

#### Goal: Initialize a Git repository and set up the basic project structure. 
Deliverable: A Git repository with a README file and a basic folder structure.
User Service - Create User
- [x] Git init

#### Goal: Develop a microservice to manage users, starting with the ability to create a user.
Deliverable: A REST API endpoint to create a user, with accompanying tests.
User Service - Retrieve User
- [ ] user creation

#### Goal: Add functionality to retrieve user details.
Deliverable: A REST API endpoint to get user details by ID, with tests.
Task Service - Create Task
- [ ] user details

#### Goal: Develop a microservice to manage tasks, starting with the ability to create a task.
Deliverable: A REST API endpoint to create a task, with accompanying tests.
Task Service - Retrieve Task
- [ ] task creation

#### Goal: Add functionality to retrieve task details.
Deliverable: A REST API endpoint to get task details by ID, with tests.
Task Service - Assign Task to User
- [ ] task details

#### Goal: Add the ability to assign a task to a user.
Deliverable: A REST API endpoint to assign a task to a user, with tests.
Integration - User-Task Assignment
- [ ] assign functionality

#### Goal: Ensure the User and Task services can interact, allowing tasks to be assigned to users.
Deliverable: End-to-end tests for user-task assignment functionality.
Task Service - Mark Task as Completed
- [ ] create e2e test

#### Goal: Add the ability to mark a task as completed.
Deliverable: A REST API endpoint to update task status, with tests.
User Service - List User's Tasks
- [ ] check marks

#### Goal: Add functionality to list all tasks assigned to a user.
Deliverable: A REST API endpoint to retrieve all tasks for a user, with tests.
Dockerize User Service
- [ ] task overview by user

#### Goal: Containerize the User service using Docker.
Deliverable: A Dockerfile for the User service, with build and run instructions.
Dockerize Task Service
- [ ] create container for user service

#### Goal: Containerize the Task service using Docker.
Deliverable: A Dockerfile for the Task service, with build and run instructions.
Docker Compose Setup
- [ ] create container for task service

#### Goal: Develop a simple frontend to interact with the backend services.
Deliverable: A basic web interface to create users, tasks, and assign tasks.
Kubernetes Deployment
- [ ] frontend completed

#### Goal: Deploy the containerized services to a Kubernetes cluster.
Deliverable: Kubernetes deployment manifests and service definitions.
Final Testing and Documentation
- [ ] kubernetes manifest for deploy for application

#### Goal: Perform final integration testing and document the project.
Deliverable: Comprehensive tests for all functionalities and detailed project documentation.
- [ ] Everything works :D
