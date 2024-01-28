## Read: Class 16

- Readings: Cloud Identity and Access Management (IAM) with AWS
Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

- Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1. What were the three commands used for the attack?

- http://169.254.169.254/iam/security-credentials
- http://169.254.169.254/iam/security-credentials/*****-WAF-Role
- CLI commands: $ aws	s3 ls / $ aws s3 sync s3://somebucket

2. What misconfiguration of AWS components allowed the attacker to access sensitive data?

- Poor security architecture design that exposed S3 buckets via AWS	WAF/EC2 instance to anyone with an IAM role.

## What are two of the AWS Governance practices that could have prevented such an attack?

- Review all access paths and	permissions from human identities or	non-human	identities. 
- Ensure each application, EC2 instance, or auto scaling group has	its own	IAM role.

## Reference

[Capital_One](https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf)

## Things I want to know more about 

- The cloud in general and cloud security particularly AWS, but all service providers would be nice.
