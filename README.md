# Udacity Nanodegree Lesson 2

In this project We created a infrastructure and EC2 servers using AWS CloudFormation

## Prerequisites

- AWS Account
- AWS Cli installed and configured with AWS account

## Run comand

To run command we helped with `create.sh` and  `update.sh` files in cloudformation folder.

Example:

```
./create.sh <stack_name> <template-body-yml> <parameters-file>

./create.sh myInfrastructure ourinfra.yml ourinfra-parameters.json

```

## Check creation status

To check te status log in with your AWS Account and go to `CloudFormation` service.