# aws_workspaces_bulk
AWS Workspaces bulk self-provisioning

If you need to build a significant number of Workspaces , this CloudFormation stack will help you to automate it.

This is simplified version based on: https://github.com/aws-samples/aws-service-catalog-reference-architectures/tree/master/bulkprovision


This CloudFormation stack will install the base component needed. It will create conponents like:
AWS Lambda
Roles for AWS Lambda
