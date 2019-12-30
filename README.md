# AWS User Group Albania WORKSHOP

AWS Logging via Console & CLI.  
AWS Elastic Beanstalk.  
CloudFormation.  
Circle CI.  
AWS EC2.  
AWS S3.  
GIT.  

## CI/CD

1- Sign in @ <https://circleci.com> (OPTIONAL: Signup with github)  
2- <https://circleci.com/add-projects> SetUP your project  
3- Choose OS and Language  
4- Start Building  

*On the properties section (Gear icon) we can add EnvVars, for ex: AWS key and secret or CI related variables.  
**For this workshop it's better to create a new user through IAM. Avoid using root!  
These permissions are all we need:  

 ```bash
 AmazonEC2FullAccess
 AmazonS3FullAccess
 AWSElasticBeanstalkFullAccess
 AWSCloudFormationFullAccess
```

## S3

1- Create stack via CF Upload or CI  

## EC2

1- Create keypair through the console  ( <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-key-pairs.html> )  
2- Create stack via CF Upload or CI  

## EB

1- Create stack via CF Upload or CI  

If created via CloudFormation console, make sure to firstly create [simple-s3.yml](cloudformation/simple-s3.yml) and then the ElasticBeanstalk stack [eb.yml](cloudformation/eb.yml)  
