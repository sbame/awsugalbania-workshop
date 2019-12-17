# AWS User Group Albania WORKSHOP

AWS Logging via Console & CLI.  
AWS Elastic Beanstalk.  
CloudFormation.  
Circle CI.  
AWS EC2.  
AWS S3.  
GIT.  

## CI/CD

1- Login with github @ <https://circleci.com>  
2- <https://circleci.com/add-projects> SetUP project  
3- Choose OS and Language  
4- Start Building  

*On the properties section (Gear icon) we can add EnvVars, for ex: AWS key and secret or CI related variables.  

## S3

1- Create stack via CF Upload or CI  

```bash
Useful commands
Remove Bucket: aws s3 rb s3://name --force
Delete Stack: aws cloudformation delete-stack --stack-name name
```

## EC2

1- Create keypair through the console  
2- Create stack via CF Upload or CI  

## EB

1- Create a bucket with an initial code zip  
2- Create stack via CF Upload or CI  
