# aws-sns-private-publishing-project
# Project 3 - Publishing Amazon SNS Messages Privately

## Objective

Create an Amazon SNS topic and publish secure messages from an EC2 instance using the AWS CLI.

## AWS Services Used

- Amazon VPC
- Amazon EC2
- Amazon SNS
- IAM
- AWS CLI

## Steps Performed

1. Created a custom VPC.
2. Created a public subnet.
3. Attached an Internet Gateway.
4. Configured a Route Table.
5. Launched an Ubuntu EC2 instance.
6. Installed AWS CLI.
7. Configured AWS CLI using IAM credentials.
8. Created an SNS topic.
9. Subscribed an email address.
10. Published messages using the AWS CLI.

## SNS Topic

HospitalReports

## Sample Publish Command

```bash
aws sns publish \
--topic-arn arn:aws:sns:us-east-1:616714047648:HospitalReports \
--message "Patient Report Uploaded Successfully"
```

## Outcome

Successfully published private messages using Amazon SNS from an EC2 instance.
