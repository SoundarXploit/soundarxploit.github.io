---
title: '𝐀𝐖𝐒 𝐒𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐂𝐡𝐞𝐜𝐤𝐥𝐢𝐬𝐭'
date: 2024-02-18
permalink: /posts/2024/04/AWSCLloud pentest/
tags:
  - Vulnerability
  - OWASP TOP 10
  - cloud security
---

𝐀𝐖𝐒 𝐒𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐂𝐡𝐞𝐜𝐤𝐥𝐢𝐬𝐭

🔹 Permit CloudTrail logging across all Amazon Web Services.

🔹Set on CloudTrail log file validation.

🔹Permit CloudTrail multi-region logging.

🔹Combine CloudTrail with CloudWatch.

🔹Permit access logging for CloudTrail S3 buckets.

🔹Permit access logging for Elastic Load Balancer (ELB).

🔹Permit Redshift audit logging.

🔹Permit Virtual Private Cloud (VPC) flow logging.

🔹Multifactor authentication (MFA) is required to delete CloudTrail buckets.

🔹Set multifactor authentication for the “root” account.

🔹Set on multifactor authentication for IAM users.

🔹Permit IAM users for multi-mode access.

🔹Link IAM policies to groups or roles.

🔹Regularly rotate IAM access keys, and standardize on the selected number of days.

🔹strict password policy must be set up

🔹Set the password termination session to 90 days

🔹Expired SSL/TLS certificates should not be used

🔹User HTTPS for CloudFront distributions.

🔹Limit access to the CloudTrail bucket.

🔹Encrypt the CloudTrail log files at rest.

🔹Elastic Block Store (EBS) database must be encrypted

🔹Provision access to resources using IAM roles.

🔹Using root user accounts should be avoided

🔹SSL secure cyphers must be applied while connecting between the client and ELB.

🔹SSL secure versions must be used while connecting between ELB and the Client.

🔹Use a standard naming (tagging) convention for EC2.

🔹Encrypt Amazon’s Relational Database Service (RDS).

🔹Access keys should not be used with root accounts.

🔹Use secure CloudFront SSL versions.

🔹Permit the require_ssl parameter in all Redshift clusters.

🔹Periodically rotate SSH keys

🔹Number of discrete security groups should be minimized

🔹Reduce the number of IAM groups.

🔹Terminate available access keys.

🔹Disable access for unused or inactive IAM users.

🔹Remove unused IAM access keys.

🔹Delete unused SSH Public Keys.

🔹Limit access to Amazon Machine Images (AMIs).

🔹Limit access to EC2 security groups.

🔹Limit access to RDS instances.

🔹Limit access to Redshift clusters.

🔹Limit access to outbound access.

🔹Disallow unrestricted ingress access on different ports.

🔹Limit access to well-known ports such as CIFS, FTP, ICMP, SMTP, SSH, and Remote desktop.

🔹Involve IT security throughout the development process.

🔹Limited privileges should be granted as possible for application users.

🔹Encrypt highly sensitive data such as personally identifiable information (PII) or protected health information (PHI)
