AWS END-TO-END CALCULATION APP

A simple end to end application built using AWS services.
The AWS End to End Calculation App is a serverless application built using various Amazon Web Services (AWS) components. It enables users to perform  simple power calculation remotely through a user-friendly interface. The app leverages services like Amazon Amplify, AWS Lambda, Amazon API Gateway, Amazon DynamoDB, and AWS IAM.
<img width="419" alt="Services that are used" src="https://github.com/Meldindavidsabu/AWSEndToEndCalculationapplication./assets/80899101/b5ac44f3-6473-4378-95c0-f0e1c80f726e">

Step 1: Set Up AWS Account
If you don't have an AWS account, create one by visiting the AWS website (https://aws.amazon.com/) and following the account creation process.

Step 2: Plan Your Application
Outline the application's architecture, features, and components. Identify the data structures needed for user input and calculation results.

Step 3: Create an Amplify App

Go to the AWS Amplify Console (https://aws.amazon.com/amplify/console/).
Upload the xip file containing the HTML file

Step 4: Set Up API Gateway and Lambda

In the AWS Management Console, navigate to Amazon API Gateway.
Create a new API and define the necessary resources and methods.
Create Lambda functions for performing power calculations.
Configure API Gateway methods to trigger the Lambda functions.
Set up API Gateway authorization to secure your APIs.

Step 5: Create DynamoDB Table

In the AWS Management Console, navigate to Amazon DynamoDB.
Create a new table to store user data and calculation results.
Define the table schema with appropriate attributes.

Step 6: Configure Lambda Access to DynamoDB

Ensure your Lambda functions have the necessary IAM roles and permissions to access DynamoDB.
Create an IAM role that grants your Lambda functions read and write access to the DynamoDB table.

Step 7: Implement Lambda Functions
Paste the Lambda functions' code to handle power calculations.

Step 8: Integrate Front-End with Backend

Configure API endpoints in your front-end code to interact with the Lambda functions through API Gateway.
Implement user authentication and authorization mechanisms using Amplify.

Step 9: Test Your Application

Test the application locally to ensure that the front-end, Lambda functions, and DynamoDB interactions work as expected.
Debug and fix any issues you encounter during testing.

Step 10: Deploy Your Application

Amplify will automatically build and deploy your application based on the configuration you set.

<img width="953" alt="calculate app final pic" src="https://github.com/Meldindavidsabu/AWSEndToEndCalculationapplication./assets/80899101/91e78161-6aa6-4dbb-b4f6-8bba93ef3134">

