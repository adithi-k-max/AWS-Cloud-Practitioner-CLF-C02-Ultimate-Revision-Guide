# DOMAIN 2 — BATCH 02

## Security & Compliance

> This batch focuses on the security services AWS repeatedly tests in CLF-C02:
>
> * IAM Roles
> * CloudTrail
> * AWS KMS
> * AWS Config
> * AWS WAF
> * AWS Shield
> * IAM Identity Center
> * Amazon Cognito

---

# Question 4 — IAM Role

## Question

According to AWS security best practices, how should an Amazon EC2 instance be granted access to an Amazon S3 bucket?

## Options

| Option | Method                                       |
| ------ | -------------------------------------------- |
| A      | Store access keys in the application code    |
| B      | Store access keys in a configuration file    |
| C      | Use an IAM Role attached to the EC2 instance |
| D      | Create a new AWS account                     |

## Correct Answer

✅ **C. Use an IAM Role Attached to the EC2 Instance**

## Why Correct?

### Keywords

* EC2
* Access S3
* Best Practice

IAM Roles provide temporary credentials securely without storing access keys.

---

## Why Others Are Wrong?

| Option | Reason                                          |
| ------ | ----------------------------------------------- |
| A      | Hardcoded credentials are a major security risk |
| B      | Configuration files can expose secrets          |
| D      | Does not solve access management                |

---

## Service: IAM Role

### Definition

Temporary AWS permissions assigned to AWS services.

### Key Features

* No hardcoded credentials
* Temporary security credentials
* Secure service-to-service access

### Exam Traps

EC2 → S3 = IAM Role

Lambda → DynamoDB = IAM Role

### Memory Trick

Humans = IAM Users

Services = IAM Roles

### Compare With

| Identity Type | Used For     |
| ------------- | ------------ |
| IAM User      | Human Access |
| IAM Role      | AWS Services |

---

# Question 605 — AWS CloudTrail

## Question

Which AWS service records API calls made within an AWS account?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | Amazon CloudWatch |
| B      | AWS Config        |
| C      | AWS CloudTrail    |
| D      | Amazon GuardDuty  |

## Correct Answer

✅ **C. AWS CloudTrail**

## Why Correct?

### Keywords

* API calls
* Audit
* Tracking activity

CloudTrail records who did what and when.

---

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| A      | Monitoring metrics     |
| B      | Configuration tracking |
| D      | Threat detection       |

---

## Service: AWS CloudTrail

### Definition

Audit logging service.

### Key Features

* API logging
* Governance
* Compliance
* Security investigations

### Exam Traps

Audit Logs = CloudTrail

Monitoring = CloudWatch

### Memory Trick

Trail Leaves Footprints.

### Compare With

| Service    | Purpose    |
| ---------- | ---------- |
| CloudTrail | Audit Logs |
| CloudWatch | Monitoring |

---

# Question 606 — AWS KMS

## Question

Which AWS service can encrypt data using customer-controlled encryption keys?

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | AWS Shield          |
| B      | AWS KMS             |
| C      | Amazon CloudFront   |
| D      | AWS Trusted Advisor |

## Correct Answer

✅ **B. AWS KMS**

## Why Correct?

KMS manages encryption keys used across AWS services.

---

## Why Others Are Wrong?

| Option | Reason                        |
| ------ | ----------------------------- |
| A      | DDoS protection               |
| C      | CDN service                   |
| D      | Best-practice recommendations |

---

## Service: AWS Key Management Service (KMS)

### Definition

Managed encryption key service.

### Key Features

* Key creation
* Key rotation
* Encryption management
* Centralized key control

### Exam Traps

Encryption Keys = KMS

### Memory Trick

KMS = Key Management Service.

### Compare With

| Service  | Purpose                 |
| -------- | ----------------------- |
| KMS      | Encryption Keys         |
| CloudHSM | Dedicated Hardware Keys |

---

# Question 488 — AWS Config

## Question

Which AWS service continuously monitors AWS resources and evaluates them against desired configurations?

## Options

| Option | Service          |
| ------ | ---------------- |
| A      | AWS Config       |
| B      | AWS CloudTrail   |
| C      | Amazon GuardDuty |
| D      | Amazon Inspector |

## Correct Answer

✅ **A. AWS Config**

## Why Correct?

### Keywords

* Evaluate configurations
* Compliance
* Continuous monitoring

AWS Config tracks and evaluates resource configurations.

---

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| B      | API audit logs         |
| C      | Threat detection       |
| D      | Vulnerability scanning |

---

## Service: AWS Config

### Definition

Configuration compliance monitoring service.

### Key Features

* Resource inventory
* Compliance checks
* Configuration history
* Change tracking

### Exam Traps

Configuration Compliance = Config

Audit Logs = CloudTrail

### Memory Trick

Config Checks Configuration.

### Compare With

| Service    | Purpose                  |
| ---------- | ------------------------ |
| Config     | Configuration Compliance |
| CloudTrail | API Auditing             |

---

# Question 489 — AWS WAF

## Question

Which AWS service helps protect web applications from SQL injection and cross-site scripting (XSS) attacks?

## Options

| Option | Service          |
| ------ | ---------------- |
| A      | AWS Shield       |
| B      | Amazon Inspector |
| C      | AWS WAF          |
| D      | Amazon GuardDuty |

## Correct Answer

✅ **C. AWS WAF**

## Why Correct?

WAF filters malicious web requests before they reach applications.

---

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | DDoS protection          |
| B      | Vulnerability assessment |
| D      | Threat detection         |

---

## Service: AWS WAF

### Definition

Web Application Firewall.

### Key Features

* SQL injection protection
* XSS protection
* Request filtering
* Rule-based security

### Exam Traps

SQL Injection = WAF

XSS = WAF

### Memory Trick

WAF Protects Websites.

### Compare With

| Service | Purpose      |
| ------- | ------------ |
| WAF     | Web Attacks  |
| Shield  | DDoS Attacks |

---

# Question 490 — AWS Shield

## Question

Which AWS service protects applications against Distributed Denial of Service (DDoS) attacks?

## Options

| Option | Service        |
| ------ | -------------- |
| A      | AWS Shield     |
| B      | AWS WAF        |
| C      | AWS Config     |
| D      | AWS CloudTrail |

## Correct Answer

✅ **A. AWS Shield**

## Why Correct?

Shield is AWS's managed DDoS protection service.

---

## Why Others Are Wrong?

| Option | Reason                                 |
| ------ | -------------------------------------- |
| B      | Protects against web attacks, not DDoS |
| C      | Configuration compliance               |
| D      | Auditing                               |

---

## Service: AWS Shield

### Definition

Managed DDoS protection service.

### Key Features

* Automatic protection
* Network-layer defense
* AWS-integrated security

### Exam Traps

DDoS = Shield

SQL Injection = WAF

### Memory Trick

Shield Blocks Attack Traffic.

### Compare With

| Service | Purpose                      |
| ------- | ---------------------------- |
| Shield  | DDoS Protection              |
| WAF     | Application Layer Protection |

---

# Question 491 — IAM Identity Center

## Question

A company wants employees to sign in once and access multiple AWS accounts and business applications.

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | IAM User            |
| B      | IAM Role            |
| C      | IAM Identity Center |
| D      | AWS CloudTrail      |

## Correct Answer

✅ **C. IAM Identity Center**

## Why Correct?

### Keywords

* Single Sign-On
* Multiple accounts
* Centralized access

IAM Identity Center provides Single Sign-On (SSO).

---

## Why Others Are Wrong?

| Option | Reason                    |
| ------ | ------------------------- |
| A      | Individual account access |
| B      | Permissions assignment    |
| D      | Audit logging             |

---

## Service: IAM Identity Center

### Definition

AWS Single Sign-On (SSO) service.

### Key Features

* Single Sign-On
* Centralized access
* Multi-account management
* Identity federation

### Exam Traps

Single Sign-On = IAM Identity Center

### Memory Trick

One Login → Many Accounts.

### Compare With

| Service             | Purpose           |
| ------------------- | ----------------- |
| IAM User            | Individual Access |
| IAM Identity Center | SSO               |

---

# Question 602 — Amazon Cognito

## Question

Which AWS service helps manage user sign-up, sign-in, and authentication for web and mobile applications?

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | Amazon Cognito     |
| B      | AWS CloudTrail     |
| C      | Amazon Route 53    |
| D      | AWS CloudFormation |

## Correct Answer

✅ **A. Amazon Cognito**

## Why Correct?

Cognito provides user authentication and identity management for applications.

---

## Why Others Are Wrong?

| Option | Reason                    |
| ------ | ------------------------- |
| B      | Auditing                  |
| C      | DNS                       |
| D      | Infrastructure deployment |

---

## Service: Amazon Cognito

### Definition

User authentication and identity service.

### Key Features

* User sign-up
* User sign-in
* Authentication
* Identity federation

### Exam Traps

App Users = Cognito

AWS Users = IAM

### Memory Trick

Customers Login → Cognito

Admins Login → IAM

### Compare With

| Service | Purpose            |
| ------- | ------------------ |
| Cognito | Application Users  |
| IAM     | AWS Administrators |

---

# Batch 02 Cheat Sheet

## 🔥 Top Services

* IAM Role
* AWS CloudTrail
* AWS KMS
* AWS Config
* AWS WAF
* AWS Shield
* IAM Identity Center
* Amazon Cognito

---

## 🔥 Top Facts To Memorize

| Concept                  | Answer              |
| ------------------------ | ------------------- |
| EC2 → S3 Access          | IAM Role            |
| API Logs                 | CloudTrail          |
| Encryption Keys          | KMS                 |
| Configuration Compliance | Config              |
| SQL Injection            | WAF                 |
| DDoS                     | Shield              |
| Single Sign-On           | IAM Identity Center |
| App Authentication       | Cognito             |

---

## 🔥 Common Exam Traps

| Question Says      | Answer     |
| ------------------ | ---------- |
| API Logs           | CloudTrail |
| Monitoring Metrics | CloudWatch |
| Vulnerability Scan | Inspector  |
| Threat Detection   | GuardDuty  |
| SQL Injection      | WAF        |
| DDoS               | Shield     |
| App User Login     | Cognito    |
| AWS Account Login  | IAM        |

---

## 🔥 Most Likely Questions To Reappear

1. GuardDuty vs Inspector
2. WAF vs Shield
3. CloudTrail vs CloudWatch
4. Cognito vs IAM
5. IAM Role vs IAM User

---

# Batch 02 Summary

```text
IAM Role            → Service Permissions
CloudTrail          → API Audit Logs
KMS                 → Encryption Keys
Config              → Configuration Compliance
WAF                 → SQL Injection / XSS Protection
Shield              → DDoS Protection
IAM Identity Center → Single Sign-On (SSO)
Cognito             → Application User Authentication
```
