# Example AWS Lambda C# .NET Core 3.0 Release though Custom Runtime (Amazon.Lambda.RuntimeSupport) with connect MySQL via not using any ORM

Example for optimize cold start with Amazon.Lambda.RuntimeSupport

## This code to show about
- Example code for using Amazon.Lambda.RuntimeSupport

## Test and Deploy with AWS CLI

**Deploy**
```
$ cd src/aws-lambda-netcore3-db
$ dotnet lambda deploy-function {LAMBDA_FUNCTION_NAME} –-function-role {ROLE_NAME}
```

**Try to Run and Get result**
```
$ cd src/aws-lambda-netcore3-db
$ aws lambda invoke --function-name {LAMBDA_FUNCTION_NAME} output.txt
```