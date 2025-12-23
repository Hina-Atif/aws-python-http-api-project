# aws-python-http-api-project
AWS Python HTTP API Project using Serverless Framework for scalable, cloud-native serverless applications

**Owner:** Hina Atif

## Project Description
This project demonstrates a Serverless Python HTTP API deployed on AWS using AWS Lambda and API Gateway.  
It provides a lightweight, scalable, and cost-efficient backend solution for handling HTTP requests without requiring server management.  

**Key Benefits:**
- Serverless architecture reduces infrastructure management overhead
- Cost-efficient: pay only for actual usage
- Highly scalable and reliable
- Easy to deploy and maintain
- Built-in monitoring via AWS CloudWatch

  ## 🖼️ Project Gallery

### 🏗️ Development & Deployment
Documentation of the project lifecycle from CLI initialization to successful cloud deployment.

| 1. Framework Initialization | 2. Python Backend Logic | 3. Deployment Success |
| :---: | :---: | :---: |
| ![Init](screenshots/01-project-init.jpeg) | ![Code](screenshots/02-backend-code.jpeg) | ![Deploy](screenshots/03-deploy-success.png) |

---

### ☁️ AWS Cloud Infrastructure
Visual proof of the serverless resources provisioned within the AWS Console.

| 4. CloudFormation Stack | 5. Resource List | 6. Lambda Console |
| :---: | :---: | :---: |
| ![Stack](screenshots/04-stack-overview.jpeg) | ![Resources](screenshots/05-stack-resources.png) | ![Lambda](screenshots/06-lambda-functions.png) |

---

### 📡 Monitoring & Testing
Configuration of API triggers and cross-platform verification (Desktop & Mobile).

| 7. API Gateway Trigger | 8. CloudWatch Logs |
| :---: | :---: |
| ![Gateway](screenshots/07-api-gateway.png) | ![Logs](screenshots/08-cloudwatch-logs.png) |

| 9. Desktop Browser Test | 10. Mobile Device Verification |
| :---: | :---: |
| ![Desktop](screenshots/09-desktop-test.jpeg) | ![Mobile](screenshots/10-mobile-output.jpeg) |

---

## Tech Stack & Tools
- **Programming Language:** Python 3.12
- **Serverless Framework:** Deployment configuration and automation
- **AWS Lambda:** Serverless compute
- **AWS API Gateway (HTTP API):** Routing and HTTP endpoint management
- **AWS CloudFormation:** Managed deployment stacks
- **AWS CloudWatch:** Logs and monitoring of Lambda functions
- **Git & GitHub:** Version control and project hosting

---

## Project Structure

aws-python-http-api-project/
├── handler.py # Lambda function logic
├── serverless.yml # Serverless Framework configuration
├── unzip_requirements.py # Script for packaging dependencies
├── README.md # Project documentation

---

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/Hina-Atif/aws-python-http-api-project.git

Deploy the API using Serverless Framework (if desired):

sls deploy (serverless deploy)

You can access the API endpoints as deployed on AWS (check Serverless output for URLs).

🚀 Deployment Screenshots

| CloudFormation Stack                                             | Lambda Functions                                        |
| ---------------------------------------------------------------- | ------------------------------------------------------- |
| ![CloudFormation Stack](screenshots/05-cloudformation-stack.png) | ![Lambda Functions](screenshots/04-aws-lambda-list.png) |



API Gateway & Monitoring
| API Triggers                                           | CloudWatch Logs                                        |
| ------------------------------------------------------ | ------------------------------------------------------ |
| ![API Gateway](screenshots/07-api-gateway-trigger.png) | ![CloudWatch Logs](screenshots/06-cloudwatch-logs.png) |




Live API Verification
| Desktop Output                                    | Mobile Output                                      |
| ------------------------------------------------- | -------------------------------------------------- |
| ![Desktop Test](screenshots/08-web-response.jpeg) | ![Mobile Test](screenshots/09-mobile-response.png) |






