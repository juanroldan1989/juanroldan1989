# Juan Roldán

### DevOps | Software Engineer | CKAD | 3x AWS Certified | Terraform & Argo Certified

Enthusiastic and versatile engineer with a proven track record of successful contributions to small, medium, and large-scale platforms.

Looking forward to driving success in diverse engineering environments, always aiming for innovation and collaboration.

# Find me

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanroldan89/) [![Substack](https://img.shields.io/badge/Substack-%23006f5c.svg?style=for-the-badge&logo=substack&logoColor=FF6719)](https://backburnerthoughts.substack.com/)

Currently focused on:

- scalability and availability solutions applying system design patterns within AWS.
- researching self-service environment/services provisioning solutions like: AWS Proton, Port and Backstage.

# Technologies

<img src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"><img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"><img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white"><img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"><img src="https://img.shields.io/badge/kubernetes-326ce5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white"><img src="https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white"><br/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"><img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"><img src="https://img.shields.io/badge/Digital_Ocean-0080FF?style=for-the-badge&logo=DigitalOcean&logoColor=white"><img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white"><img src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"><img src="https://img.shields.io/badge/circleci-343434?style=for-the-badge&logo=circleci&logoColor=white"><img src="https://img.shields.io/badge/travis_CI-3EAAAF?style=for-the-badge&logo=travisci&logoColor=white"><br/>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white"><img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white">

# Portfolio (continuously developed)

## Events Live Tracking App (AWS ECS)

Events Tracking Platform 🚦 Clicks & Hovers on Colors 🎯 Live Graphs & Counters

https://github.com/juanroldan1989/color-tracking

<img width="800" src="https://github.com/juanroldan1989/color-tracking/blob/main/color-tracking-live-demo.gif" />
<img width="800" src="https://github.com/juanroldan1989/serverless-color-tracking/raw/main/screenshots/serverless-color-tracking-admin-page-demo.gif" />

- User events information stored in database (**PostgreSQL** & **Redis** supported).
- Events stats shared via **Action Cable** and displayed to subscribed clients or specific clients via **polling** JS requests.
- Backend implementd with **Ruby on Rails**, **Kafka** and **Zookeeper**.
- Deployment workflow through **AWS ECS** script.
- Deployment workflow through **Terraform** and integrated within **Github Actions** (CI/CD) into **AWS**. (work in progress)
- **Alternative Implementation** - API Infrastructure and business logic provisioned via **Serverless** framework - https://github.com/juanroldan1989/serverless-url-shortener

<hr>

## URL Shortener API (Terraform)

API Infrastructure provisioned via **Terraform (IaC)** - https://github.com/juanroldan1989/terraform-url-shortener

<img src="https://github.com/juanroldan1989/terraform-url-shortener/raw/main/screenshots/title-image.png" width="100%" />
<img src="https://github.com/juanroldan1989/serverless-url-shortener/raw/main/screenshots/serverless-shortener-infra-1.png" width="100%" />

- Implemented with **AWS Lambda Functions**, **NodeJS** and **CQRS** Pattern.
- Infrastructure managed through **Terraform**.
- Deployment workflow through **Terraform** and integrated within **Github Actions** (CI/CD) into **AWS**.
- **API Load Testing** results obtained through **Artillery**. Integrated within Github actions.
- **TDD** applied across every development level.
- **Alternative Implementation** - API Infrastructure and business logic provisioned via **Serverless** framework - https://github.com/juanroldan1989/serverless-url-shortener

<hr>

## AWS ECS Blueprints

https://github.com/juanroldan1989/deploy-ecs-blueprint

Showcase with several combinations of ECS Service + ECS Task + Nginx + Python + Databases

![Screenshot 2024-09-30 at 12 28 13](https://github.com/user-attachments/assets/20bef5c8-8723-40b9-92be-be8427a8ee5e)

![Screenshot 2024-09-30 at 20 19 25](https://github.com/user-attachments/assets/ecff068b-8af2-47ff-a18d-798d63f033e4)

![Screenshot 2024-09-30 at 13 33 36](https://github.com/user-attachments/assets/160b9f43-e588-4c50-a015-ff5e8ceaf430)

Features provided within each blueprint:

- 🟢 Software Development Lifecycle (SDLC) pipeline integrated within `Github Actions`
- 🟢 Infrastructure provisioned through `Terraform`
- 🟢 Autoscaling mechanisms provided
- 🟡 `Terraform` State and locking mechanism handled within `S3` and `DynamoDB` **(work in progress)**
- 🟡 Load Testing performed through `wrk` and `k6s` tools **(work in progress)**

<hr>

## Terra Ops

https://github.com/juanroldan1989/terra-ops

<img src="https://github.com/juanroldan1989/terra-ops/blob/main/terra-ops-logo.png" alt="juanroldan1989 terra-ops">

This project structure allows engineers to:

- work in authorized environments linked to Terraform workspaces
- update modules as needed
- deploy specific applications or modules, like networking or ArgoCD apps within their respective environments

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

<hr>

## REST API (Terraform & AWS Lambda)

https://github.com/juanroldan1989/terraform-with-rest-api-gateway-and-lambda-functions

<img src="https://github.com/juanroldan1989/terraform-with-rest-api-gateway-and-lambda-functions/raw/main/screenshots/custom-auth-workflow.png" width="100%" />

- Implemented with **AWS Lambda Functions** and **NodeJS**.
- Authorization Layer implemented through **AWS Lambda Authorizer**.
- Infrastructure managed through **Terraform**.
- Deployment workflow through **Terraform** and integrated within **Github Actions** (CI/CD) into **AWS**.
- **API Load Testing** results obtained through **Artillery**. Integrated within Github actions.
- **TDD** applied across every development level.

<hr>

## Cocktails API

https://cocktailsapi.xyz/

Providing engineers with THE best dataset of cocktails & drinks from all over the world.

<img src="https://media.giphy.com/media/zd1VtTAjLRHNe/giphy.gif" width="100%" />

- [Shaken Not Stirred](https://github.com/juanroldan1989/shaken_not_stirred) API Ruby client ;)
- Have a 🍹 and start coding!

<hr>

## Personal quotes

- "Looking for discomfort in comfortable ways."
- "Don't confuse unfamiliarity with complexity."
- "To have something you never had, you have to do something you never did."

## Thoughts on the best work environment

I believe the best place to work is the one where _I can evolve and challenge myself in projects while collaborating with amazing people_ and working on platforms that improve people's lives on a daily basis.

Every time I go outside my comfort zone, I find myself traveling to unvisited corners of my mind, felling closely to untapped emotions, watching hidden desires become visible for the first time and I always come back to this:

_The only constant throughout my life has been my desire to communicate and build._

**I communicate** by working on challenging projects, writing and condensing a decade worth of experience within my development blog, performing live music mixes, looking for outdoor activities and chess matches.

**I build** through software and infrastructure, system design, piano tunes, writing and sketching.
