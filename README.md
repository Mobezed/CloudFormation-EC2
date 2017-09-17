# CloudFormation-EC2
Create an Ubuntu EC2 instance with S3 bucket and a  static Webpage.

Instruction to run AWS CF template (using AWS CLI):-

aws cloudformationcreate-stack --stack-name STACK_NAME --template-url https://s3.amazonaws.com/BUCKET_NAME/CloudFormation_EC2.json --parameters  ParameterKey=KeyName,ParameterValue=YOUR_KEY_NAME
