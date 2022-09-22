# AWS Ventura CloudFormation Project

## AWS CloudFormation CLI Commands
- **AWS CLI Documentation:** https://docs.aws.amazon.com/cli/latest/reference/cloudformation/create-stack.html

- **Create Stack Command:** 
aws cloudformation create-stack \
--stack-name Ventura-Prod-Env-Infrastructure \
--template-body file://Ventura-Prod-Env-Infra.yaml \
--parameters file://Ventura-Prod-Env-Infra-Parameter-File.json

- **Delete Stack Command:**
aws cloudformation delete-stack \
    --stack-name Ventura-Prod-Env-Infrastructure