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
git clone https://github.com/hinaatif001/aws-python-http-api-project.git

Deploy the API using Serverless Framework (if desired):

sls deploy (serverless deploy)

You can access the API endpoints as deployed on AWS (check Serverless output for URLs).



