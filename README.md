# Sample EC2 Template for AWS Cloud Formation

## Basic Requirements:

- AWS Account

- IAM User with aws cli, ec2 create/delete instance and cloud formation create/delete permission

- AWS CLI

# Usage

Copy and run in aws cli
```
aws cloudformation create-stack \
  --stack-name YourStackName \
  --template-body lamp-stack-template.yml \
  --parameters ParameterKey=KeyName,ParameterValue=YourKeyName
```

To check status
```
aws cloudformation describe-stacks --stack-name YourStackName
```


