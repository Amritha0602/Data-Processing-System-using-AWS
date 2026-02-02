DATA PROCESSING USING AWS

Project Overview:
This project shows how to process student data using AWS serverless services.
Student details are sent from a server, stored safely, and a notification is sent automatically.

AWS Services Used:
EC2 – Runs the application/server
SQS – Queue to send student data
Lambda – Processes the data
DynamoDB – Stores student details
S3 – Stores student data files
SNS – Sends notification messages
IAM – Controls permissions

Project Flow:
Student data is sent from EC2
Data goes to SQS queue
Lambda reads the data
Lambda stores data in:
DynamoDB
S3
Lambda sends notification using SNS

Why This Project?
To understand AWS serverless architecture
To learn how multiple AWS services work together
To build a real-time data processing system

Key Learnings:
AWS Lambda basics
Using SQS for messaging
Storing data in DynamoDB and S3
Sending notifications using SNS
IAM role and permissions

Future Improvements:
Add monitoring using CloudWatch
Add error handling with DLQ
Add API Gateway for frontend access

Author
AMRITHA SS
