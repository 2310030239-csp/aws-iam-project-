\# AWS IAM Project: EC2 Access via Policy and S3 Access via Group



\## Overview

This project demonstrates how to create an IAM user who has:

\- EC2 access through a directly attached IAM policy.

\- S3 access through an IAM group with S3 permissions.



\## Steps Performed

1\. Created an IAM group named `S3AccessGroup`.

2\. Attached `AmazonS3FullAccess` policy to the group.

3\. Created an IAM user named `ec2-s3-user`.

4\. Attached `AmazonEC2FullAccess` policy directly to the user.

5\. Added the user to `S3AccessGroup`.

6\. Verified permissions using AWS Management Console and AWS CLI.



\## Tools Used

\- AWS Free Tier Account

\- IAM Service

\- EC2 Service

\- S3 Service



\## Output

\- User can launch and manage EC2 instances.

\- User can upload and manage objects in S3 buckets.

