# Portfolio

## Sisyphus

A practical guide to modern infrastructure provisioning and application deployment.

DevOps-centric project that demonstrates modern infrastructure provisioning and application deployment workflows.

This project allows DevOps engineers and Cloud Architects to:

1. Operate within **specific** environments to which they have access.
2. **Add or remove** modules as necessary to build applications within their designated environments.
3. Deploy targeted applications or modules (e.g., **networking**, **karpenter**, **eks/internal-app**) within their specific environments.

Each environment folder (e.g., **dev**, **prod**) corresponds to a specific cloud environment.

Repository: https://github.com/juanroldan1989/sisyphus

<hr>

## High-Performance Data Processing Project

This project focuses on the complete automation of a high-performance data processing system.

Repository: https://github.com/juanroldan1989/10K-users-for-10M-records

### Features

- **Data Population**: Efficiently populate a database with 10 million weather data records.
- **Health Check**: Execute standard health check queries on the database to ensure data integrity and performance.
- **Application Deployment**: Deploy a Flask application using GUnicorn and Nginx for optimal performance.
- **Load Simulation**: Simulate 10,000 users per second interacting with the API to test system scalability and robustness.
- **Performance Tracking**: Monitor and document performance metrics and improvements.
- **Containerization**: Ensure all components are containerized from the outset, adhering to best practices.
- **Development & Testing**: Facilitate seamless development and testing using Docker Compose and Terraform.
- **CI/CD Integration**: Integrate with GitHub Actions for continuous integration and deployment (work in progress).
- **Infrastructure Provisioning**: Use Terraform for provisioning infrastructure on AWS ECS Fargate (work in progress).

<hr>

## Events Live Tracking App

The Events Tracking Platform is designed to monitor user interactions such as clicks and hovers on various colors, providing real-time graphs and counters.

Repository: https://github.com/juanroldan1989/color-tracking

### Features

- **Data Storage**: User events are stored in databases with support for both **PostgreSQL** and **Redis**.
- **Real-Time Updates**: Event statistics are shared via **Action Cable** for real-time updates to subscribed clients, or through polling JavaScript requests for specific clients.
- **Backend Implementation**: The backend is developed using **Ruby on Rails**, **Kafka**, and **Zookeeper**.
- **Deployment**:
  - Primary deployment workflow is managed through **AWS ECS** scripts.
  - Infrastructure as Code (IaC) is handled using **Terraform**, with CI/CD integration via **GitHub Actions** into **AWS** (work in progress).
- **Alternative Implementation**: An alternative implementation of the API infrastructure and business logic is available using the **Serverless** framework. [Serverless Color Tracking](https://github.com/juanroldan1989/serverless-color-tracking)

<hr>

## URL Shortener API

URL Shortener API infrastructure is provisioned using **Terraform (IaC)**.

Repository: https://github.com/juanroldan1989/terraform-url-shortener

### Features

- **Implementation**: Developed with **AWS Lambda Functions**, **NodeJS**, and the **CQRS** pattern.
- **Infrastructure Management**: Managed entirely through **Terraform**.
- **Deployment Workflow**: Automated deployment using **Terraform**, integrated with **GitHub Actions** for CI/CD into **AWS**.
- **API Load Testing**: Performance testing conducted using **Artillery**, with results integrated into GitHub Actions.
- **Test-Driven Development (TDD)**: Applied across all development stages.
- **Alternative Implementation**: An alternative version of the API infrastructure and business logic is available using the **Serverless** framework. The repository can be found at [serverless-url-shortener](https://github.com/juanroldan1989/serverless-url-shortener).

<hr>

## Kubernetes Monitoring with Prometheus & cAdvisor & Grafana

### CPU Usage Demo

#### Load Testing (Start)

- `rating-ns` deployment
- HPA enabled for deployment
- Grafana Dashboards and Panels showcased

https://github.com/user-attachments/assets/0fb3b5b5-0732-4712-8798-cf8a6592262b

https://github.com/user-attachments/assets/4b55b0b8-dd18-4b36-9535-fd7dfa14b65c

#### Load Testing (Ending)

- `infinite-requests` deployment deleted -> load testing source removed

https://github.com/user-attachments/assets/d4e01624-e66f-4d26-afa8-57b35dbce782

- `HPA` terminating pods based on null CPU consumption

https://github.com/user-attachments/assets/2a885781-689a-417f-be15-c57542ed07d8
