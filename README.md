# Sample EC2 Template for AWS Cloud Formation

## Basic Requirements:

- AWS Account

- IAM User with aws cli, ec2 create/delete instance and cloud formation create/delete permission

- AWS CLI

# Usage
Open AWS CLI copy and paste commands:

To create stack and run the yml file
```
aws cloudformation create-stack \
  --stack-name YourStackName \
  --template-body ec2lampstack.yml
```
To check status
```
aws cloudformation describe-stacks --stack-name YourStackName
```
To delete stack and its resources created
```
aws cloudformation delete-stack --stack-name YourStackName
```


