# AWS EventBridge + Lambda Automation Project

## Project Overview
This project demonstrates an event-driven serverless architecture using Amazon EventBridge
to automatically trigger an AWS Lambda function based on defined rules.

## Services Used
- Amazon EventBridge
- AWS Lambda (Python)
- AWS IAM
- Amazon CloudWatch

## How the Project Works
1. An EventBridge rule is created to listen for a specific event or schedule.
2. When the event occurs, EventBridge triggers the Lambda function.
3. The Lambda function executes Python code.
4. Execution details are logged in Amazon CloudWatch.

## Use Case
This project can be used for automating tasks such as:
- Scheduled jobs (cron-like tasks)
- Event-based processing
- Serverless workflows without managing servers

## Folder Structure
- lambda_code/ → Contains AWS Lambda Python code
- architecture/ → Architecture diagram of the project
- screenshots/ → AWS Console screenshots
- permissions/ → IAM role and policy
- notes/ → Simple project explanation

## Outcome
Successfully built and tested an automated event-driven workflow using AWS EventBridge
and AWS Lambda following serverless best practices.

