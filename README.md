# Trifork Evaluation for Sathis Anarudhan

## This Repository includes one AWS Cloud formation deployment script, which deploy below services in AWS with required IAM role base access
   1. REST API in Api Gateway with three GET services
   2. DynamoDB with three tables
   3. Lambda Function with boto3 framework to scan and query the database via API call
   4. AWS cloudwatch to monitor the above 3 deployments
