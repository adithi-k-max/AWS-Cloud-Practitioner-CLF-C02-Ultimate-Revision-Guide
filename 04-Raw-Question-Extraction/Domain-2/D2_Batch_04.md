DOMAIN 2 — SECURITY & COMPLIANCE — FINAL BATCH

This is the final sweep of the remaining high-yield Security & Compliance concepts that repeatedly appear in CLF-C02.

Question #8
Question

According to the AWS Shared Responsibility Model, who is responsible for patching the physical infrastructure that supports AWS services?

Options

A. Customer

B. AWS Partner

C. AWS

D. Third-party vendor

Correct Answer

✅ C. AWS

Why Correct?

AWS manages:

Physical servers
Storage devices
Networking hardware
Data centers
Why Others Are Wrong?

A Customer
Only manages resources inside AWS.

B AWS Partner
Not responsible for AWS infrastructure.

D Third-party vendor
Not applicable.

SERVICE: Shared Responsibility Model
Definition

AWS secures the cloud infrastructure.

Exam Trap

Physical Hardware = AWS

Operating System on EC2 = Customer

Question #605 Variant
Question

A security team needs to determine which IAM user deleted an Amazon EC2 instance.

Which AWS service should they use?

Options

A. CloudWatch

B. CloudTrail

C. GuardDuty

D. Macie

Correct Answer

✅ B. AWS CloudTrail

Why Correct?

CloudTrail records:

API calls
User activity
Resource actions
Why Others Are Wrong?

A CloudWatch
Metrics and monitoring.

C GuardDuty
Threat detection.

D Macie
Sensitive data discovery.

SERVICE: CloudTrail
Definition

AWS audit logging service.

Key Features
Who did what
When it happened
Which resource was affected
Memory Trick

CloudTrail = Security CCTV.

Question #620
Question

Which AWS service enables customers to control encryption keys used to encrypt AWS resources?

Options

A. AWS KMS

B. IAM

C. CloudTrail

D. Route 53

Correct Answer

✅ A. AWS KMS

Why Correct?

KMS handles:

Encryption keys
Key rotation
Key policies
Why Others Are Wrong?

B IAM
Permissions.

C CloudTrail
Auditing.

D Route53
DNS.

SERVICE: AWS KMS
Definition

Managed encryption key service.

Exam Trap

Encryption Keys = KMS

Encryption itself often uses KMS-managed keys.

Question #621
Question

A company wants to secure its AWS account root user.

Which action follows AWS best practices?

Options

A. Create access keys for root user

B. Share root credentials

C. Enable MFA on root user

D. Use root user for daily administration

Correct Answer

✅ C. Enable MFA on root user

Why Correct?

Root user should have:

MFA enabled
Minimal usage
Why Others Are Wrong?

A
Avoid root access keys.

B
Never share credentials.

D
Use IAM users instead.

SERVICE: Root User Security
Definition

Best practices for protecting the AWS account owner account.

Key Features
MFA
Emergency use only
Exam Trap

Root User = Rarely Used

Question #622
Question

Which AWS service helps evaluate AWS resources against compliance rules continuously?

Options

A. AWS Config

B. CloudTrail

C. Route53

D. SNS

Correct Answer

✅ A. AWS Config

Why Correct?

Config evaluates resources continuously.

Why Others Are Wrong?

B
Logs activity.

C
DNS.

D
Notifications.

SERVICE: AWS Config
Definition

Compliance monitoring service.

Key Features
Compliance rules
Configuration history
Resource inventory
Exam Trap

Compliance Monitoring = Config

Audit Logs = CloudTrail

Question #623
Question

Which AWS service provides protection against SQL injection attacks?

Options

A. Shield

B. WAF

C. Inspector

D. Macie

Correct Answer

✅ B. AWS WAF

Why Correct?

WAF filters malicious HTTP requests.

Why Others Are Wrong?

A Shield
DDoS protection.

C Inspector
Vulnerability assessment.

D Macie
Sensitive data detection.

SERVICE: AWS WAF
Definition

Web Application Firewall.

Key Features
SQL injection protection
Cross-site scripting protection
Exam Trap

Web attacks = WAF

DDoS = Shield

Question #624
Question

A company wants a centralized dashboard for security findings collected from multiple AWS security services.

Options

A. Security Hub

B. CloudFormation

C. Lambda

D. Route53

Correct Answer

✅ A. AWS Security Hub

Why Correct?

Security Hub aggregates findings.

Why Others Are Wrong?

B
Infrastructure deployment.

C
Serverless compute.

D
DNS.

SERVICE: AWS Security Hub
Definition

Centralized security findings dashboard.

Key Features
Aggregates GuardDuty
Aggregates Inspector
Aggregates Macie
Memory Trick

Security Hub = Security Headquarters.

DOMAIN 2 MASTER CHEAT SHEET
🔥 Security Services Comparison
Service	Purpose
IAM	Permissions
IAM Role	Service Access
IAM Identity Center	Single Sign-On
Cognito	App User Authentication
CloudTrail	Audit Logs
CloudWatch	Monitoring
Config	Compliance Monitoring
GuardDuty	Threat Detection
Inspector	Vulnerability Scanning
Macie	Sensitive Data Discovery
Security Hub	Central Security Dashboard
Shield	DDoS Protection
WAF	SQL Injection & XSS Protection
KMS	Encryption Keys
Artifact	Compliance Reports
🔥 20 Facts You Must Memorize
EC2 → S3 access = IAM Role
API Logs = CloudTrail
Metrics = CloudWatch
Threat Detection = GuardDuty
Vulnerability Scan = Inspector
Sensitive Data = Macie
Security Dashboard = Security Hub
SQL Injection = WAF
DDoS = Shield
Encryption Keys = KMS
Compliance Reports = Artifact
Compliance Monitoring = Config
Single Sign-On = IAM Identity Center
App Authentication = Cognito
MFA on Root User
Least Privilege Principle
Security Group = Instance Firewall
NACL = Subnet Firewall
AWS manages Hardware
Customer manages IAM & Data
🎯 Domain 2 Completion Status

For Cloud Practitioner exam preparation purposes:

✅ IAM — Covered
✅ Roles — Covered
✅ MFA — Covered
✅ Shared Responsibility — Covered
✅ CloudTrail — Covered
✅ Config — Covered
✅ KMS — Covered
✅ WAF — Covered
✅ Shield — Covered
✅ GuardDuty — Covered
✅ Inspector — Covered
✅ Macie — Covered
✅ Security Hub — Covered
✅ Cognito — Covered
✅ IAM Identity Center — Covered
✅ Artifact — Covered
✅ Security Groups — Covered
✅ NACLs — Covered

Domain 2 is effectively complete for CLF-C02 revision.
