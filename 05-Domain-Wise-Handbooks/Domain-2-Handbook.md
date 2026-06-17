# Domain 2 Handbook — Security & Compliance (CLF-C02)

## Overview

Domain 2 (Security & Compliance) contributes approximately 30% of the AWS Certified Cloud Practitioner (CLF-C02) exam.

This is one of the highest-scoring domains because AWS repeatedly asks questions around:

- IAM
- IAM Users
- IAM Roles
- MFA
- Shared Responsibility Model
- Security Groups
- Network ACLs
- Cognito
- IAM Identity Center
- AWS Organizations
- CloudTrail
- AWS Config
- KMS
- WAF
- Shield
- GuardDuty
- Inspector
- Macie
- Security Hub
- Artifact

Unlike Domain 1, which focuses on cloud concepts, Domain 2 focuses on securing AWS resources, identities, data, and workloads.

---

# Chapter 1 — Security Fundamentals

## Definition

Security in AWS is built around:

- Identity Management
- Access Control
- Data Protection
- Monitoring
- Threat Detection
- Compliance

AWS follows a shared responsibility approach between AWS and the customer.

---

## Core Security Goals

### Confidentiality

Only authorized users can access data.

### Integrity

Data remains accurate and unmodified.

### Availability

Systems remain accessible when needed.

---

## AWS Security Model

Security consists of:

- Authentication
- Authorization
- Encryption
- Monitoring
- Auditing
- Threat Detection

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| User permissions | IAM |
| Encryption keys | KMS |
| Threat detection | GuardDuty |
| Vulnerability scanning | Inspector |
| Audit logs | CloudTrail |

---

# Chapter 2 — Shared Responsibility Model

## Definition

AWS follows the Shared Responsibility Model.

AWS secures:

> Security OF the Cloud

Customers secure:

> Security IN the Cloud

---

## AWS Responsibilities

AWS manages:

- Physical servers
- Data centers
- Networking hardware
- Storage hardware
- Global infrastructure
- Power
- Cooling

---

## Customer Responsibilities

Customers manage:

- IAM permissions
- Data
- Security groups
- Network ACLs
- Encryption settings
- EC2 operating systems
- Application security

---

## Exam Traps

### AWS Responsibility

- Physical Security
- Hardware
- Facilities
- Global Network

### Customer Responsibility

- Data
- IAM
- Access Permissions
- EC2 Operating Systems

---

## Memory Trick

AWS = OF the Cloud

Customer = IN the Cloud

---

# Chapter 3 — IAM Fundamentals

## Definition

IAM (Identity and Access Management) controls:

- Authentication
- Authorization
- Permissions

for AWS resources.

---

## Purpose

IAM allows administrators to:

- Create users
- Create groups
- Create roles
- Assign permissions

---

## Benefits

- Centralized access control
- Fine-grained permissions
- Secure resource access
- Least privilege enforcement

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Permissions | IAM |
| Access Control | IAM |
| User Management | IAM |

---

# Chapter 4 — IAM Users

## Definition

An IAM User represents a person or application that needs access to AWS.

---

## Examples

- Administrator
- Developer
- Tester
- DevOps Engineer

---

## Characteristics

- Permanent identity
- Username
- Password
- Optional access keys

---

## Best Practices

- Enable MFA
- Avoid sharing accounts
- Rotate credentials
- Follow least privilege

---

## Exam Trap

Human User = IAM User

---

# Chapter 5 — IAM Groups

## Definition

IAM Groups are collections of IAM Users.

---

## Purpose

Simplify permission management.

---

## Example

Developers Group

Members:

- User A
- User B
- User C

Assign permissions once.

All members inherit them.

---

## Benefits

- Easier management
- Consistent permissions
- Reduced administration

---

## Exam Trap

Many Users Same Permissions

Answer:

✅ IAM Group

---

# Chapter 6 — IAM Policies

## Definition

IAM Policies are JSON documents that define permissions.

---

## Purpose

Control:

- Allowed actions
- Denied actions
- Resource access

---

## Example

Allow:

- Read S3

Deny:

- Delete S3

---

## Types

### AWS Managed Policies

Created by AWS.

### Customer Managed Policies

Created by customers.

### Inline Policies

Attached directly to a user, group, or role.

---

## Exam Trap

Permissions Document

Answer:

✅ IAM Policy

---

# Chapter 7 — IAM Roles

## Definition

IAM Roles provide temporary permissions.

---

## Difference Between User and Role

| IAM User | IAM Role |
|-----------|-----------|
| Permanent Identity | Temporary Identity |
| Human Access | Service Access |
| Long-Term Credentials | Temporary Credentials |

---

## Common Examples

### EC2 → S3

Use IAM Role

### Lambda → DynamoDB

Use IAM Role

### ECS → S3

Use IAM Role

---

## Benefits

- No hardcoded credentials
- Temporary access
- More secure

---

## Exam Trap

Question Says:

EC2 accessing S3

Answer:

✅ IAM Role

---

## Memory Trick

Humans = Users

Services = Roles

---

# Chapter 8 — IAM Best Practices

## AWS Recommendations

### Enable MFA

For all users.

### Rotate Credentials

Regularly update credentials.

### Use Least Privilege

Grant only required permissions.

### Use IAM Roles

Avoid storing access keys.

### Avoid Root User

Use IAM users instead.

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Extra security | MFA |
| Minimum permissions | Least Privilege |
| Temporary permissions | IAM Role |

---

# Chapter 9 — Multi-Factor Authentication (MFA)

## Definition

MFA adds a second authentication factor.

---

## Authentication Factors

### Something You Know

Password

### Something You Have

Authenticator App

Security Key

Phone

---

## Benefits

- Stronger security
- Protection against password theft
- Reduced account compromise risk

---

## AWS Recommendation

Enable MFA on:

- Root User
- IAM Users

---

## Exam Trap

Additional Authentication Layer

Answer:

✅ MFA

---

## Memory Trick

Password + Device = MFA

---

# Chapter 10 — Least Privilege Principle

## Definition

Users receive only the permissions required to perform their jobs.

---

## Benefits

- Reduced attack surface
- Better security
- Lower risk

---

## Example

Developer needs:

- Read S3

Do NOT grant:

- AdministratorAccess

---

## Exam Trap

Minimum Required Permissions

Answer:

✅ Least Privilege

---

## Memory Trick

Need-To-Know Access Only

---

# Chapter 11 — Root User Security

## Definition

The Root User is the AWS account owner.

---

## Characteristics

- Full permissions
- Cannot be restricted
- Created automatically

---

## Best Practices

### Enable MFA

Always.

### Avoid Daily Usage

Use IAM users.

### Do Not Share Credentials

Never share root account.

### Avoid Root Access Keys

Do not create unless absolutely necessary.

---

## Exam Trap

Root User Best Practice

Answer:

✅ Enable MFA

---

## Memory Trick

Root User = Emergency Use Only

---

# Chapter 12 — IAM Identity Center

## Definition

IAM Identity Center provides Single Sign-On (SSO).

---

## Purpose

Allow users to access:

- Multiple AWS Accounts
- Business Applications

with one login.

---

## Benefits

- Centralized access
- SSO
- Simplified administration

---

## Exam Trap

Question Says:

Single Sign-On

Multiple AWS Accounts

Answer:

✅ IAM Identity Center

---

## Memory Trick

One Login → Many Accounts

---

# Chapter 13 — Amazon Cognito

## Definition

Amazon Cognito provides authentication for application users.

---

## Purpose

Allows users to:

- Sign Up
- Sign In
- Authenticate

within applications.

---

## Examples

- Mobile Apps
- Web Apps
- SaaS Platforms

---

## Features

- User registration
- User authentication
- Social logins
- Identity federation

---

## Exam Trap

App User Authentication

Answer:

✅ Cognito

---

## Compare With IAM

| Service | Purpose |
|-----------|-----------|
| IAM | AWS Users |
| Cognito | Application Users |

---

## Memory Trick

Customers Login = Cognito

Admins Login = IAM

---

# Chapter 14 — AWS Organizations

## Definition

AWS Organizations allows centralized management of multiple AWS accounts.

---

## Features

- Central governance
- Account management
- Organizational Units (OUs)
- Policy management
- Consolidated billing

---

## Benefits

- Easier administration
- Cost visibility
- Central security controls

---

## Exam Trap

Question Says:

Manage Multiple Accounts

Answer:

✅ AWS Organizations

---

## Memory Trick

Many Accounts → Organizations

---

# Chapter 15 — Security Groups

## Definition

A Security Group is a virtual firewall that controls traffic at the EC2 instance level.

It determines:

- Who can access an instance
- Which ports are open
- Which protocols are allowed

---

## Characteristics

- Instance-level firewall
- Stateful
- Allow rules only
- Automatically allows return traffic

---

## Example

Web Server:

Allow:

- HTTP (80)
- HTTPS (443)

Deny:

Everything else by default

---

## Benefits

- Instance protection
- Fine-grained access control
- Simple security management

---

## Exam Trap

Question Says:

- EC2 firewall
- Instance-level protection
- Allow specific ports

Answer:

✅ Security Group

---

## Memory Trick

Security Group = Security Guard For One Building

---

# Chapter 16 — Network ACLs (NACLs)

## Definition

A Network Access Control List (NACL) is a virtual firewall that controls traffic at the subnet level.

---

## Characteristics

- Subnet-level firewall
- Stateless
- Supports Allow rules
- Supports Deny rules
- Rule order matters

---

## Example

Subnet:

Allow:

- HTTP
- HTTPS

Deny:

- Specific IP range

---

## Security Group vs NACL

| Security Group | NACL |
|---------------|-------|
| Instance Level | Subnet Level |
| Stateful | Stateless |
| Allow Only | Allow & Deny |
| Return Traffic Automatic | Return Traffic Must Be Allowed |

---

## Exam Trap

Question Says:

- Subnet firewall
- Deny specific IPs
- Rule order matters

Answer:

✅ NACL

---

## Memory Trick

NACL = Neighborhood Firewall

---

# Chapter 17 — Security Groups vs Network ACLs

## Most Common CLF-C02 Comparison

| Feature | Security Group | NACL |
|----------|---------------|------|
| Scope | Instance | Subnet |
| Stateful | Yes | No |
| Stateless | No | Yes |
| Allow Rules | Yes | Yes |
| Deny Rules | No | Yes |
| Rule Order Matters | No | Yes |

---

## Exam Trap

Instance Firewall

Answer:

✅ Security Group

Subnet Firewall

Answer:

✅ NACL

---

# Chapter 18 — AWS CloudTrail

## Definition

CloudTrail records API activity inside AWS.

It answers:

- Who performed an action?
- What action occurred?
- When did it occur?

---

## Examples

Track:

- EC2 deletion
- IAM modifications
- S3 policy changes
- User logins

---

## Key Features

- Audit logging
- Governance
- Compliance
- Security investigations

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| API Calls | CloudTrail |
| Audit Logs | CloudTrail |
| User Activity | CloudTrail |

---

## Exam Trap

Monitoring Metrics ≠ CloudTrail

CloudTrail = Audit

---

## Memory Trick

Trail Leaves Footprints

---

# Chapter 19 — Amazon CloudWatch (Security Perspective)

## Definition

CloudWatch monitors AWS resources and workloads.

---

## What It Monitors

- CPU usage
- Memory metrics
- Disk activity
- Network traffic
- Application metrics

---

## Features

- Metrics
- Alarms
- Dashboards
- Monitoring

---

## Exam Trap

Question Says:

- Monitor performance
- Monitor EC2
- CPU alarms

Answer:

✅ CloudWatch

---

## Compare With CloudTrail

| Service | Purpose |
|-----------|-----------|
| CloudWatch | Monitoring |
| CloudTrail | Auditing |

---

## Memory Trick

Watch = Monitor

Trail = Audit

---

# Chapter 20 — AWS Config

## Definition

AWS Config continuously evaluates AWS resources against desired configurations.

---

## Purpose

Tracks:

- Resource inventory
- Configuration history
- Compliance status

---

## Features

- Continuous compliance
- Configuration monitoring
- Resource tracking

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Compliance Monitoring | Config |
| Resource Configuration | Config |
| Configuration History | Config |

---

## Exam Trap

Config = Compliance

CloudTrail = Audit

---

## Memory Trick

Config Checks Configuration

---

# Chapter 21 — AWS Artifact

## Definition

AWS Artifact provides on-demand access to compliance reports and security documentation.

---

## Examples

- SOC Reports
- ISO Certifications
- Compliance Reports

---

## Features

- Self-service portal
- Compliance reports
- Security certifications

---

## Exam Trap

Question Says:

- Compliance documentation
- Audit reports
- Certifications

Answer:

✅ AWS Artifact

---

## Memory Trick

Artifact = Documents

---

# Chapter 22 — AWS Key Management Service (KMS)

## Definition

AWS KMS manages encryption keys.

---

## Purpose

Used for:

- Creating keys
- Managing keys
- Rotating keys
- Controlling encryption

---

## Features

- Key creation
- Key rotation
- Key policies
- Centralized encryption

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Encryption Keys | KMS |
| Customer Controlled Keys | KMS |

---

## Exam Trap

Encryption Keys = KMS

---

## Memory Trick

KMS = Key Management Service

---

# Chapter 23 — Encryption Fundamentals

## Definition

Encryption converts readable data into unreadable data.

---

## Purpose

Protect:

- Data at Rest
- Data in Transit

---

## Data At Rest

Stored data.

Examples:

- S3 Objects
- EBS Volumes
- RDS Databases

---

## Data In Transit

Moving data.

Examples:

- HTTPS
- TLS
- SSL

---

## Exam Trap

Question Says:

- Protect stored data
- Encrypt AWS resources

Answer:

✅ Encryption

---

# Chapter 24 — AWS WAF

## Definition

AWS WAF (Web Application Firewall) protects web applications from common web attacks.

---

## Protects Against

- SQL Injection
- Cross-Site Scripting (XSS)
- Malicious requests

---

## Features

- Request filtering
- Web protection
- Application security

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| SQL Injection | WAF |
| XSS | WAF |
| Web Application Protection | WAF |

---

## Exam Trap

SQL Injection = WAF

DDoS = Shield

---

## Memory Trick

WAF Protects Websites

---

# Chapter 25 — AWS Shield

## Definition

AWS Shield provides protection against Distributed Denial of Service (DDoS) attacks.

---

## Types

### Shield Standard

Included automatically.

### Shield Advanced

Additional protection.

---

## Features

- DDoS protection
- Network-layer protection
- Automatic defense

---

## Exam Trap

Question Says:

- DDoS attack
- Traffic flood
- Availability attack

Answer:

✅ AWS Shield

---

## Compare With WAF

| Service | Purpose |
|-----------|-----------|
| WAF | SQL Injection & XSS |
| Shield | DDoS Protection |

---

## Memory Trick

Shield Blocks Attack Traffic

---

# Chapter 26 — Amazon GuardDuty

## Definition

GuardDuty is AWS's intelligent threat detection service.

---

## Monitors

- CloudTrail Logs
- DNS Logs
- VPC Flow Logs

---

## Detects

- Suspicious activity
- Malicious behavior
- Unauthorized access

---

## Features

- Threat detection
- Continuous monitoring
- Security intelligence

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Threat Detection | GuardDuty |
| Suspicious Activity | GuardDuty |

---

## Exam Trap

Threat Detection = GuardDuty

Vulnerability Scan = Inspector

---

## Memory Trick

GuardDuty Guards AWS

---

# Chapter 27 — Amazon Inspector

## Definition

Amazon Inspector scans workloads for vulnerabilities.

---

## Scans

- EC2
- ECR
- Lambda

---

## Finds

- Vulnerabilities
- Missing patches
- Security issues

---

## Features

- Vulnerability scanning
- Security assessments
- Continuous evaluation

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Vulnerability Scan | Inspector |
| Security Assessment | Inspector |

---

## Exam Trap

Inspector = Vulnerabilities

GuardDuty = Threats

---

## Memory Trick

Inspector Inspects Systems

---

# Chapter 28 — Amazon Macie

## Definition

Amazon Macie discovers sensitive data stored in Amazon S3.

---

## Detects

- PII
- Sensitive information
- Data exposure risks

---

## Examples

- Credit card numbers
- Personal information
- Confidential records

---

## Features

- Data classification
- Sensitive data discovery
- Risk visibility

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Sensitive Data | Macie |
| PII Detection | Macie |
| S3 Data Discovery | Macie |

---

## Exam Trap

Sensitive Data In S3

Answer:

✅ Macie

---

## Memory Trick

Macie Searches S3 Buckets

---

# Chapter 29 — AWS Security Hub

## Definition

AWS Security Hub provides a centralized dashboard for security findings across AWS services.

---

## Purpose

Aggregates findings from:

- Amazon GuardDuty
- Amazon Inspector
- Amazon Macie
- AWS Partner Security Tools

---

## Benefits

- Single security dashboard
- Centralized visibility
- Compliance monitoring
- Easier investigations

---

## Features

- Security score
- Compliance checks
- Finding aggregation
- Security recommendations

---

## Exam Keywords

| Question Says | Answer |
|--------------|---------|
| Central Security Dashboard | Security Hub |
| Security Findings Aggregation | Security Hub |
| Security Visibility | Security Hub |

---

## Exam Trap

Question Says:

- Centralized security findings
- One dashboard for security

Answer:

✅ Security Hub

---

## Memory Trick

Security Hub = Security Headquarters

---

# Chapter 30 — AWS Compliance Overview

## Definition

Compliance refers to meeting legal, regulatory, and industry standards.

---

## Examples

- ISO
- SOC
- PCI DSS
- HIPAA

---

## AWS Compliance Services

- AWS Artifact
- AWS Config
- Security Hub

---

## Benefits

- Regulatory adherence
- Audit readiness
- Risk reduction

---

## Exam Trap

Compliance Reports

Answer:

✅ AWS Artifact

Compliance Monitoring

Answer:

✅ AWS Config

---

# Chapter 31 — Identity and Access Security

## Core Services

### IAM

Controls AWS user permissions.

### IAM Roles

Temporary permissions for services.

### IAM Identity Center

Single Sign-On.

### Cognito

Application user authentication.

---

## Exam Comparison

| Service | Purpose |
|-----------|-----------|
| IAM | AWS User Permissions |
| IAM Role | Service Permissions |
| IAM Identity Center | Single Sign-On |
| Cognito | App User Authentication |

---

# Chapter 32 — Data Protection Overview

## Definition

Data protection ensures data remains:

- Confidential
- Secure
- Available

---

## Core Protection Mechanisms

### Encryption

Protects data.

### IAM

Controls access.

### KMS

Manages keys.

### Macie

Detects sensitive data.

---

## Exam Trap

Sensitive Data Discovery

Answer:

✅ Macie

Encryption Keys

Answer:

✅ KMS

---

# Chapter 33 — Monitoring vs Auditing vs Compliance

## Monitoring

Observe resource performance.

Service:

✅ CloudWatch

---

## Auditing

Track user activity.

Service:

✅ CloudTrail

---

## Compliance

Evaluate configurations.

Service:

✅ AWS Config

---

## Comparison Table

| Requirement | Service |
|-------------|----------|
| Monitoring | CloudWatch |
| Audit Logs | CloudTrail |
| Compliance Monitoring | Config |

---

## Exam Trap

Metrics

Answer:

✅ CloudWatch

API Activity

Answer:

✅ CloudTrail

Configuration Compliance

Answer:

✅ Config

---

# Chapter 34 — Threat Detection vs Vulnerability Assessment

## Threat Detection

Identifies suspicious behavior.

Service:

✅ GuardDuty

---

## Vulnerability Assessment

Finds weaknesses and security issues.

Service:

✅ Inspector

---

## Comparison Table

| Service | Purpose |
|-----------|-----------|
| GuardDuty | Threat Detection |
| Inspector | Vulnerability Scanning |

---

## Exam Trap

Threat Detection

Answer:

✅ GuardDuty

Vulnerability Scan

Answer:

✅ Inspector

---

# Chapter 35 — Security Service Mega Comparison

| Service | Purpose |
|-----------|-----------|
| IAM | Permissions |
| IAM Role | Service Access |
| IAM Identity Center | Single Sign-On |
| Cognito | App Authentication |
| CloudTrail | Audit Logs |
| CloudWatch | Monitoring |
| Config | Compliance |
| KMS | Encryption Keys |
| WAF | Web Protection |
| Shield | DDoS Protection |
| GuardDuty | Threat Detection |
| Inspector | Vulnerability Assessment |
| Macie | Sensitive Data Discovery |
| Security Hub | Security Dashboard |
| Artifact | Compliance Reports |

---

# Chapter 36 — WAF vs Shield

## AWS WAF

Protects against:

- SQL Injection
- Cross-Site Scripting (XSS)
- Malicious Web Requests

---

## AWS Shield

Protects against:

- DDoS Attacks
- Availability Attacks
- Traffic Flooding

---

## Comparison Table

| Service | Purpose |
|-----------|-----------|
| WAF | Web Application Attacks |
| Shield | DDoS Attacks |

---

## Exam Trap

SQL Injection

Answer:

✅ WAF

DDoS

Answer:

✅ Shield

---

# Chapter 37 — GuardDuty vs Inspector vs Macie

## GuardDuty

Detects threats.

Examples:

- Suspicious API calls
- Credential compromise
- Malicious behavior

---

## Inspector

Finds vulnerabilities.

Examples:

- Missing patches
- Security weaknesses

---

## Macie

Discovers sensitive data.

Examples:

- PII
- Financial records
- Personal information

---

## Comparison Table

| Service | Purpose |
|-----------|-----------|
| GuardDuty | Threat Detection |
| Inspector | Vulnerability Scanning |
| Macie | Sensitive Data Discovery |

---

## Exam Trap

Threat

Answer:

✅ GuardDuty

Vulnerability

Answer:

✅ Inspector

Sensitive Data

Answer:

✅ Macie

---

# Chapter 38 — Root User Protection

## AWS Recommendations

### Enable MFA

Always.

### Avoid Daily Usage

Use IAM users.

### Do Not Share Credentials

Never share root credentials.

### Avoid Root Access Keys

Do not create unless required.

---

## Root User Checklist

✅ Enable MFA

✅ Store credentials securely

✅ Use only for account-level tasks

✅ Create IAM administrators

---

## Exam Trap

Root User Best Practice

Answer:

✅ Enable MFA

---

# Chapter 39 — Security Best Practices

## Principle of Least Privilege

Grant only required permissions.

---

## Enable MFA

For:

- Root User
- IAM Users

---

## Use IAM Roles

Avoid hardcoded credentials.

---

## Rotate Credentials

Regularly update credentials.

---

## Monitor Activity

Use:

- CloudTrail
- CloudWatch

---

## Protect Sensitive Data

Use:

- Encryption
- KMS
- Macie

---

## Continuous Compliance

Use:

- AWS Config
- Security Hub

---

# Chapter 40 — Shared Responsibility Master Table

| Responsibility | AWS | Customer |
|---------------|-----|----------|
| Data Centers | ✅ | ❌ |
| Physical Servers | ✅ | ❌ |
| Networking Hardware | ✅ | ❌ |
| Storage Hardware | ✅ | ❌ |
| IAM Permissions | ❌ | ✅ |
| Customer Data | ❌ | ✅ |
| Security Groups | ❌ | ✅ |
| NACLs | ❌ | ✅ |
| EC2 OS Patching | ❌ | ✅ |
| Application Security | ❌ | ✅ |

---

# Chapter 41 — Most Common Domain 2 Exam Traps

| Question Says | Answer |
|--------------|---------|
| API Logs | CloudTrail |
| Monitoring | CloudWatch |
| Compliance Monitoring | Config |
| Compliance Reports | Artifact |
| Encryption Keys | KMS |
| SQL Injection | WAF |
| DDoS Protection | Shield |
| Threat Detection | GuardDuty |
| Vulnerability Scan | Inspector |
| Sensitive Data Discovery | Macie |
| Security Dashboard | Security Hub |
| Single Sign-On | IAM Identity Center |
| App Authentication | Cognito |
| Service Permissions | IAM Role |
| Root Security | MFA |
| EC2 → S3 Access | IAM Role |
| Instance Firewall | Security Group |
| Subnet Firewall | NACL |
| Physical Security | AWS |
| IAM Permissions | Customer |

---

# Chapter 42 — Domain 2 Final Revision Sheet

Know these instantly:

- Shared Responsibility Model
- IAM
- IAM Users
- IAM Groups
- IAM Policies
- IAM Roles
- MFA
- Least Privilege
- Root User Security
- IAM Identity Center
- Amazon Cognito
- AWS Organizations
- Security Groups
- Network ACLs
- CloudTrail
- CloudWatch
- AWS Config
- AWS Artifact
- AWS KMS
- Encryption
- AWS WAF
- AWS Shield
- Amazon GuardDuty
- Amazon Inspector
- Amazon Macie
- AWS Security Hub

---

# Chapter 43 — Domain 2 Master Comparison Table

| Concept | Meaning |
|----------|----------|
| IAM | Permissions |
| IAM Role | Service Access |
| MFA | Extra Security Layer |
| CloudTrail | Audit Logs |
| CloudWatch | Monitoring |
| Config | Compliance |
| KMS | Encryption Keys |
| WAF | SQL Injection Protection |
| Shield | DDoS Protection |
| GuardDuty | Threat Detection |
| Inspector | Vulnerability Scanning |
| Macie | Sensitive Data Discovery |
| Security Hub | Security Dashboard |
| Artifact | Compliance Reports |
| Security Group | Instance Firewall |
| NACL | Subnet Firewall |
| Cognito | App Authentication |
| IAM Identity Center | Single Sign-On |

---

# Domain 2 Completion Status

✅ Security Fundamentals

✅ Shared Responsibility Model

✅ IAM

✅ IAM Users

✅ IAM Groups

✅ IAM Policies

✅ IAM Roles

✅ IAM Best Practices

✅ MFA

✅ Least Privilege

✅ Root User Security

✅ IAM Identity Center

✅ Cognito

✅ AWS Organizations

✅ Security Groups

✅ Network ACLs

✅ CloudTrail

✅ CloudWatch

✅ AWS Config

✅ AWS Artifact

✅ AWS KMS

✅ Encryption

✅ AWS WAF

✅ AWS Shield

✅ Amazon GuardDuty

✅ Amazon Inspector

✅ Amazon Macie

✅ AWS Security Hub

✅ Security Best Practices

✅ Compliance Concepts

✅ Domain 2 Exam Traps

✅ Domain 2 Final Revision Sheet

For AWS Certified Cloud Practitioner (CLF-C02) preparation, Domain 2 is now fully covered.
