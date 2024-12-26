# BoardgameListingWebApp

## Description
🚀This isn't just a pipeline - it's a full-blown, end-to-end CI/CD masterpiece! 🌟🎉

🛠️ Key technologies and tools used:

🔧 Jenkins: Open-source CI/CD automation server with extensive plugin support. ☕ Java JDK: Java Development Kit for compiling and running Java applications. 🏗️ Maven: Build automation and project management tool for Java projects. 🔍 SonarQube: Tool for continuous code quality inspection and vulnerability detection. 🔒 Trivy: Open-source security scanner for containers and file systems. 📦 Nexus: Repository manager for storing and distributing build artifacts. 🐳 Docker: Platform for developing and running containerized applications. ☸️ Kubernetes: Container orchestration platform for automated deployment and scaling. ☁️ AWS: Cloud platform providing a wide range of services for computing, storage, and networking. 🌳 Git: Version control system for tracking changes in source code during software development. 📊 Prometheus: Open-source monitoring system for collecting and querying time series metrics. 📈 Grafana: Visualization platform for creating customizable dashboards from various data sources.

Here's a breakdown of my pipeline:

🔍 Git Checkout: Pulls the latest code from the main branch. 🛠️ Compile: Compiles the Java code using Maven. 🧪 Test: Runs unit tests with Maven. 🔬 File System Scan: Performs a security scan of the file system using Trivy. 🔍 SonarQube Analysis: Analyzes code quality with SonarQube. 🚦 Quality Gate: Checks if the code meets quality standards. 📦 Build: Packages the application with Maven. 📤 Publish to Nexus: Uploads the built artifact to Nexus repository. 🐳 Docker Image Build: Creates a Docker image of the application. 🔬 Docker Image Scan: Scans the Docker image for vulnerabilities using Trivy. 📤 Docker Image Push: Pushes the Docker image to a repository. 🚀 Deploy to Kubernetes: Applies Kubernetes manifests to deploy the application. ✅ Verify Deployment: Checks the status of pods and services in Kubernetes. 📧 Email Notification: Sends an email with the pipeline status and report

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊
