# Serverless Cloud Dictionary

## Project Overview
Serverless Cloud Dictionary is a cloud-based web application that allows users to search cloud computing terms and view their definitions in real time.  
The application is built using a fully serverless architecture on Amazon Web Services (AWS).

This project demonstrates practical implementation of AWS serverless services, API integration, and cloud deployment.

---

## Key Features
- Cloud term search functionality
- Real-time data retrieval
- Serverless backend architecture
- Scalable NoSQL database
- Web-based user interface
- Deployed using AWS services

---

## Technology Stack

### Frontend
- HTML
- CSS
- JavaScript  
- AWS Amplify (Hosting)

### Backend
- AWS Lambda
- AWS API Gateway (HTTP API)
- Amazon DynamoDB
- IAM Roles and Policies

---

## System Architecture
Client → API Gateway → AWS Lambda → DynamoDB

---

## Application Workflow
1. User enters a cloud computing term in the frontend
2. Request is sent to AWS API Gateway
3. API Gateway triggers an AWS Lambda function
4. Lambda queries Amazon DynamoDB using the partition key
5. Definition is returned as a JSON response
6. Frontend displays the result to the user

---

## Cloud Concepts Implemented
- Serverless computing
- Event-driven architecture
- REST API integration
- NoSQL database design
- IAM-based access control
- CORS handling
- AWS Free Tier usage

---

## Deployment Details
- Frontend deployed using AWS Amplify
- Backend deployed using AWS Lambda
- API managed with AWS API Gateway
- Database managed using Amazon DynamoDB
- Region: AWS Asia Pacific (Mumbai)

---

## Learning Outcomes
- Hands-on experience with AWS serverless services
- Understanding of Lambda and API Gateway integration
- DynamoDB data modeling and querying
- Cloud application deployment
- Debugging real-world CORS and API routing issues

---

## Author
Kirti

---

## Project Type
Academic / Self-Learning / Cloud Project

---

## Keywords
AWS, Serverless, AWS Lambda, DynamoDB, API Gateway, Cloud Computing, Web Application, AWS Amplify, NoSQL Database
