# template-aws-lambda

⚠️ This is Work In Progress

A GitHub template for any AWS Lambda serverless function called by an API Gateway with custom domain. 

## Key features

* API Gateway uses a custom domain api.example.org
* each reprository branch is mapped through a base path mapping, e.g. api.example.org/develop/
* each branch creates a separate Cloudformation Stack consisting of a separate API Gateway and Lambda
* branch deletion causes cleanup of corresponding AWS resources

## Setup

TBD