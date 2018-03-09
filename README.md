# serverless-dynamodb
Serverless basic functionality using aws lamda and dynamodb

Setps to Install
1. Install Serverless framework globally. sudo npm install -g serverless

Create an IAM user in aws console. Get access key and secrete key after finishing user creation.

Enter IAM keys in the serverless configuration. serverless config credentials --provider aws --key Access Key --secret Secrete Key With this an account gets connected to serverless and will be saved as default profile.

Create boilerplate template for creating services: serverless create --template aws-nodejs --name serverless-rest-api --path serverless-rest-api Get into the serverless folder cd serverless-rest-api/

Install dependencies npm install --save aws-sdk uuid
