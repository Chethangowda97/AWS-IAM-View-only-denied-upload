# AWS-IAM-View-only-denied-upload

IAM User with Read-Only Access to a Specific S3 Bucket
Project Overview

This project demonstrates how to implement the Principle of Least Privilege in AWS by creating an IAM user with read-only access to a specific Amazon S3 bucket.

The IAM user is allowed to:

>> View the list of S3 buckets (for AWS Console access)
Access a specific S3 bucket
Download objects from that bucket

>> The IAM user is restricted from:
Uploading objects
Deleting objects
Modifying existing objects

>> AWS Services Used
AWS Identity and Access Management (IAM)
Amazon Simple Storage Service (S3)

>> Implementation Steps
Created an S3 bucket named besant-task-2.
Uploaded a sample object to the bucket.
Created an IAM user named besant-2.
Created a custom inline IAM policy.
Attached the policy to the IAM user.
Verified access by logging in as the IAM user.

>> 
