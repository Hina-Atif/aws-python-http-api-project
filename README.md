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


![01-project-init](https://github.com/user-attachments/assets/adab3970-ee79-4d2b-9776-114e4edde101)
![02-python-logic](https://github.com/user-attachments/assets/b9e904fd-72f8-43b2-9ca7-f287a676b9df)
![03-deploy-success png](https://github.com/user-attachments/assets/8df1315a-8da6-494f-84c1-e9af3d9b2240)
![04-aws-lambda-list png](https://github.com/user-attachments/assets/f975b219-040d-4d58-bf9d-241eb24bd407)
![05-cloudformation-stack png](https://github.com/user-attachments/assets/2cbcc88b-2141-4d7f-b246-dc9f2ec7e858)
![06-cloudwatch-logs png](https://github.com/user-attachments/assets/4fa6547f-6c0f-4100-89d0-5ec77d09d030)
![07-api-gateway-trigger png](https://github.com/user-attachments/assets/58c7e51b-0da4-4f80-86cb-17aef5026e28)
![08-web-response](https://github.com/user-attachments/assets/5ff3717a-64e7-4e00-a768-cfa69d11df84)
![09-web-response2](https://github.com/user-attachments/assets/136fe460-a718-483e-8908-166247c2eb2c)
![WhatsApp Image 2025-12-22 at 8 27 36 PM](https://github.com/user-attachments/assets/47560416-4344-4023-b1f6-0532b7151baa)






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






