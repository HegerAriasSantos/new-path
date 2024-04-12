# new-path


path

- [ ] DSA
    - [ ] Beginning
        - [ ] Arrays
        - [ ] Linked Lists
        - [ ] Queue
        - [ ] Recursion ( factorial, fibonacci)
        - [ ] Sorting (insertion, merge, quick, bucket)
        - [ ] Binary Search
        - [ ] Trees ( binary, binary search, BST Insert and remove, DFS, BST Sets and Maps)
        - [ ] Backtracking (Tree Maze)
        - [ ] Heap/Priority Queue 
        - [ ] Hashing ( implementation)
        - [ ] Graphs (Matrix BFS, Matrix BFS, Adjacency List)
        - [ ] Dynamic Programming ( 1 and 2 dimensions DP)
        - [ ] Bit Manipulation
        - [ ] Stack
    - [ ] 	- Advanced
    - [ ] 		Follow this path using the explanation video and the problems in every topic: https://neetcode.io/courses/advanced-algorithms/0


System Design Beginners
	- For this topic search for goods resources but In the beginning you can use this one : https://neetcode.io/courses/system-design-for-beginners/0
	
	-As a final test design a whole project from a big tech for example: https://neetcode.io/courses/system-design-interview/3
	-Then design a microservice system with:
    - [ ] 2 languages ( Node, C#)
    - [ ] 2 databases ( sql server or postgresql and mongodb)
    - [ ] authentication by JWT and google auth
    - [ ] All inside dockers containers
    - [ ] Kubernetes for the management
    - [ ] CI/CD whole enterprise pipelines 
        - [ ] Use Husky for run linter before commit and something like that for C#
        - [ ] Run Test in every upload code and notify if the test doesn't pass
        - [ ] Deploy to some free server when push to main branch
    - [ ] Implement my own Dems to setup a local developer environment, dems actions:
        - [ ] create a folders structure for whole system
        - [ ] Git clone to every project 
        - [ ] run the docker-compose up for every project
    - [ ] Every project got to has his own dockerfile with all things they need ( database, application, etc...)


chatgpt Idea:  		Service Architecture:
    * Node.js Service: This service can handle user authentication using JWT and Google Auth. It will be responsible for user management and authentication.
    * C# Service: This service will handle the core business logic of your application. It can interact with both SQL Server/PostgreSQL and MongoDB databases as needed.
* 		Databases:
    * SQL Server/PostgreSQL: For structured data.
    * MongoDB: For unstructured or semi-structured data.
* 		Authentication:
    * Implement JWT and Google Auth in the Node.js service. Use libraries like jsonwebtoken for JWT and Google Auth libraries for Node.js.
    * Utilize OAuth 2.0 protocol for Google authentication.
* 		Containerization:
    * Dockerize each service individually.
    * Each database instance should also run in its own Docker container.
* 		Orchestration:
    * Use Kubernetes for container orchestration. It will help in scaling, managing, and deploying containers.
* 		CI/CD Pipeline:
    * Use Jenkins, GitLab CI/CD, or GitHub Actions for CI/CD pipelines.
    * Implement Husky for running linters before commits.
    * Run tests automatically on every code push using a testing framework like Jest for Node.js and NUnit for C#.
    * Configure notifications for failed tests.
    * Automate deployment to a staging environment upon successful testing.
    * Deploy to a free server (like Heroku or AWS Free Tier) when pushing to the main branch.
* 		Custom Deployment Scripts:
    * Develop custom deployment scripts using shell scripts or any preferred scripting language.
    * Create a folder structure for the entire system.
    * Use Git clone to fetch the latest code for each project.
    * Run docker-compose up for each project to spin up the containers.
* 		Dockerfiles:
    * Each service should have its own Dockerfile specifying all the dependencies needed for that service.
    * Include Dockerfiles for databases with appropriate configurations.
* 		Version Control:
    * Utilize Git for version control.
    * Maintain separate repositories for each service and database.
* 		Monitoring and Logging:
    * Integrate logging and monitoring tools like ELK stack (Elasticsearch, Logstash, and Kibana) or Prometheus and Grafana for monitoring containerized applications.
This approach will ensure a scalable, maintainable, and robust microservice system with CI/CD pipelines, containerization, orchestration, and custom deployment scripts.



or 

* 		Authentication Service:
    * Language: Node.js
    * Database: PostgreSQL (for user data)
    * JWT for authentication
    * Google Auth integration
* 		User Service:
    * Language: C#
    * Database: MongoDB (for user-related data)
    * Handles user-related operations such as profile management
* 		Product Service:
    * Language: Node.js
    * Database: PostgreSQL (for product data)
    * Manages product catalog and inventory
* 		Order Service:
    * Language: C#
    * Database: MongoDB (for order-related data)
    * Manages order processing and fulfillment
* 		Frontend Service:
    * Language: Node.js (for server-side rendering)
    * Database: None
    * Handles frontend operations, serves UI to clients
* 		CI/CD Pipeline:
    * Use Husky for pre-commit hooks (linting, etc.) for Node.js projects.
    * Use similar tools for C# projects.
    * Run tests using Jest for Node.js projects and NUnit for C# projects.
    * Deployment to a Kubernetes cluster managed by a CI/CD tool (e.g., Jenkins, GitLab CI) when changes are pushed to the main branch.
* 		Developer Environment Setup (DEMS):
        * Write a script in Node.js or Bash to:
        * Create a folder structure for the entire system.
        * Clone each project's Git repository.
        * Run docker-compose up for each project, ensuring all dependencies are started.
* 		Dockerfile for Each Project:
    * Each project should have its own Dockerfile specifying all necessary dependencies (including databases, application server, etc.).



or 

Microservices Architecture:
* 		Authentication Service:
    * Language: Node.js
    * Database: PostgreSQL for user data
    * Authentication: JWT and Google Auth
* 		User Service:
    * Language: C#
    * Database: MongoDB for user-related data
    * Authentication: JWT (interacts with Authentication Service)
* 		Product Service:
    * Language: Node.js
    * Database: MongoDB for product data
    * Authentication: JWT (interacts with Authentication Service)
* 		Order Service:
    * Language: C#
    * Database: PostgreSQL for order data
    * Authentication: JWT (interacts with Authentication Service)

