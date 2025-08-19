Prerequisites

An S3 Bucket, An IAM Role For ec2 instance (jenkins instance with s3, Dynamodb, ec2 full access) & Dynamodb Table (use LockID (string)) 
can create an s3 bucket & Dynamodb Table via terraform or Manually 


Here we have Definead The Desired state of Infrastructure In Terraform config files and Implemented These Configurations via Jenkins.
 
The Jenkins pipeline is Configured in a way that we can create or destroy our infra using the pipeline.


