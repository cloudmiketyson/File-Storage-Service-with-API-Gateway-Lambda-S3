## Implementing a file storage service for user content using API Gateway, Lambda, S3, and Cloudfront distribution

### Create a Serverless file upload service where **authenticated** users can securely upload files to an S3 bucket through an API Gateway endpoint and process the uploaded files using Lambda functions.

##### File Storage Service Web app hosted in S3 and API Gatweay & Lambda for the backend    -  *Completed*
    

Architecture
![Alt text](architecture-api-gateway.gif)

provide values to the following variables to when running terraform plan/apply:

| Field                 | Value               |
|-----------------------|---------------------|
| AWS Region            | `<your_region>`     |
| AWS Account ID        | `<your_account_id>` |
| User Bucket           | `<user_bucket>`     |
| Lambda Function Name  | `<lambda_func_name>`|
| Lambda Runtime        | `python3.8`         |
| WebApp Bucket         | `<webapp_bucket>`   |

Medium article link: https://towardsaws.com/implementing-a-file-storage-service-for-user-content-using-api-gateway-lambda-and-s3-part-1-2c5b2d1ae67c