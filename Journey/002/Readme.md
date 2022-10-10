# Logging and Monitoring in AWS

## Introduction

Amazon Web Services (AWS) logging and monitoring is a set of practices you can use to verify the security and performance of your AWS resources and data. These practices rely on various tools and services to collect, analyze, and present data insights. You can then use these insights to identify vulnerabilities and issues, predict performance, and optimize configurations.

## Use Case

Logging and monitoring is very important to monitor data from all parts of an AWS account. Logs are very important to keep track of compliance requirement and troubleshooting issues

## Cloud Research

- Database logs - help you detect queries that are slow to run.
- Application logs - point out application failures.
- AWS CloudTrail - detects API calls made to AWS.
- Elastic Load Balancing and host logs - might indicate availability or latency changes.
- OS logs - can identify host failure reasons.
- Web server logs - as well as firewall logs and VPC flow logs can detect patterns of access and attacks.

Audit points:

- Is a cloud trail enabled on the AWS account / AWS organization?
- Is the cloud trail applied to all the AWS regions
- Is CloudTrail log file integrity enabled
- Is cloudWatch logs enabled
- Does logging takes place in a dedicated and centralized S3 bucket
- Is least privilege access implemented to Amazon S3 buckets where you store log files
- Check if Amazon GuardDuty enabled to check for any malicious activities in the AWS accounts
- Review Identity and Access Management (IAM) credentials report

## Social Proof

[Twitter](https://twitter.com/saucyvip3r/status/1579531076716101633)
