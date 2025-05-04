1.**AWS Resource Lister Script**


This is a Bash script that automates the listing of various AWS resources in a specified region using the AWS CLI.

2.**Features**

Supports multiple AWS services

Accepts region and service as input parameters

Provides quick visibility into your AWS resource inventory

Easy to extend for additional services

3.**Supported AWS Services**


Service	Description
ec2	Lists all EC2 instances
rds	Lists all RDS database instances
s3	Lists all S3 buckets
cloudfront	Lists all CloudFront distributions
vpc	Lists all VPCs
iam	Lists all IAM users
route53	Lists all Route53 hosted zones
cloudwatch	Lists all CloudWatch alarms
cloudformation	Lists all CloudFormation stacks
lambda	Lists all Lambda functions
sns	Lists all SNS topics
sqs	Lists all SQS queues
dynamodb	Lists all DynamoDB tables
ebs	Lists all EBS volumes

Note: The script has a typo where route53 is written as route5. It should be corrected before use.

4.**Prerequisites**


AWS CLI must be installed and available in your system's PATH

AWS CLI must be configured with valid credentials (aws configure)

A Unix-like environment with Bash

Usage
bash
Copy
Edit
./aws_resource_list.sh <aws_region> <aws_service>
Example
bash
Copy
Edit
./aws_resource_list.sh us-east-1 ec2
This command lists all EC2 instances in the us-east-1 region.

5.**Installation**


Clone the repository or download the aws_resource_list.sh script.

6.**Make the script executable:**

bash
Copy
Edit
chmod +x aws_resource_list.sh
Run it with the required parameters.

7.**Author**


Rakshit Soratur
Version: v0.1
