# Deploying Serverless Web App on AWS: S3, API Gateway, Lambda, DynamoDB, and CloudFront


# Serverless Student Database Web Application on AWS

Welcome to this repo, here is how to deploy a serverless student database web application using various AWS services. 
This app can serve multiple purposes in student and data administration, offering a scalable and secure solution for data management.

## What You'll Learn:
1. **Hosting Static Web Content with S3**: We'll start by creating an S3 bucket to host the app's static files, such as HTML, CSS, and JavaScript, enabling a seamless front-end experience.
   
2. **API Gateway for Backend Requests**: Learn how to configure API Gateway to trigger Lambda functions that handle both `GET` and `POST` requests, allowing interaction with a DynamoDB database.

3. **Lambda Functions for Business Logic**: We'll implement Lambda functions in Python to manage requests to and from the DynamoDB database, performing operations like data retrieval and insertion.

4. **DynamoDB for Data Storage**: Set up a DynamoDB table for efficient data storage, including defining table schemas and performing CRUD operations via Lambda.

5. **Secure Delivery with CloudFront**: Finally, we'll use CloudFront to serve our static content securely over HTTPS, enhancing security and performance through content delivery optimization.

## Outcome:
By following this tutorial, you’ll deploy a fully functional serverless web app that can efficiently handle user interactions, store student data in DynamoDB, and deliver content securely using CloudFront.

---

### Key AWS Services:
- **S3**: For hosting static content.
- **API Gateway**: To manage and route API requests.
- **Lambda**: For serverless function execution.
- **DynamoDB**: For fast and scalable data storage.
- **CloudFront**: For secure and efficient content delivery.

Start building and mastering serverless architecture today! 🚀
