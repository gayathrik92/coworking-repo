This project utilizes Flask as the backend framework, SQLAlchemy for ORM and database management, and Docker for containerization. The application is deployed on Kubernetes using Amazon EKS (Elastic Kubernetes Service), and continuous integration and delivery are managed through AWS CodeBuild and CodePipeline. Environment-specific configurations, such as database credentials and application settings, are handled securely via Kubernetes Secrets and ConfigMaps.

The following documentation provides an overview of the deployment pipeline and how developers can release new builds, manage application configuration, and update deployments.

**Technologies and Tools**
Flask: Lightweight Python web framework for building APIs and web applications.
SQLAlchemy: ORM used to interact with a PostgreSQL database, handling object-relational mapping and migrations.
Docker: Containerization tool for packaging the application with its dependencies.
Amazon EKS: Kubernetes service hosted on AWS, used for deploying and managing the application in production.
AWS CodeBuild: Managed build service to compile the source code, run tests, and package the application into Docker images.
AWS CodePipeline: Automates the deployment of new builds from source to production.
Kubernetes ConfigMap and Secrets: Kubernetes resources to manage configuration and sensitive information like database credentials.
