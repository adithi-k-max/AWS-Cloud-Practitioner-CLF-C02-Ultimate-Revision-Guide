# DOMAIN 2 — FINAL BATCH

## Security & Compliance

> This final batch covers the remaining high-yield Security & Compliance concepts frequently tested in CLF-C02.
>
> Focus Areas:
>
> * Shared Responsibility Model
> * Root User Security
> * CloudTrail
> * KMS
> * AWS Config
> * AWS WAF
> * AWS Security Hub

---

# Question 8 — Shared Responsibility Model

## Question

According to the AWS Shared Responsibility Model, who is responsible for patching the physical infrastructure that supports AWS services?

## Options

| Option | Entity             |
| ------ | ------------------ |
| A      | Customer           |
| B      | AWS Partner        |
| C      | AWS                |
| D      | Third-Party Vendor |

## Correct Answer

✅ **C. AWS**

## Why Correct?

AWS manages:

* Physical servers
* Storage devices
* Networking hardware
* Data centers

---

## Why Others Are Wrong?

| Option | Reason                                                  |
| ------ | ------------------------------------------------------- |
| A      | Customer manages resources inside AWS                   |
| B      | AWS Partners are not responsible for AWS infrastructure |
| D      | Not applicable                                          |

---

## Service: Shared Responsibility Model

### Definition

AWS secures the cloud infrastructure.

Customers secure their resources within AWS.

### Exam Traps

Physical Hardware = AWS

Operating System on EC2 = Customer

### Memory Trick

AWS = Security OF the Cloud

Customer = Security IN the Cloud

---

# Question 605 Variant — AWS CloudTrail

## Question

A security team needs to determine which IAM user deleted an Amazon EC2 instance.

Which AWS service should they use?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | CloudWatch |
| B      | CloudTrail |
| C      | GuardDuty  |
| D      | Macie      |

## Correct Answer

✅ **B. AWS CloudTrail**

## Why Correct?

CloudTrail records:

* API calls
* User activity
* Resource actions
* Account events

---

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | Monitoring and metrics   |
| C      | Threat detection         |
| D      | Sensitive data discovery |

---

## Service: AWS CloudTrail

### Definition

AWS audit logging service.

### Key Features

* Who performed an action
* When it happened
* Which resource was affected
* Governance and compliance support

### Exam Traps

Audit Logs = CloudTrail

Metrics = CloudWatch

### Memory Trick

CloudTrail = Security CCTV

---

# Question 620 — AWS KMS

## Question

Which AWS service enables customers to control encryption keys used to encrypt AWS resources?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | AWS KMS    |
| B      | IAM        |
| C      | CloudTrail |
| D      | Route 53   |

## Correct Answer

✅ **A. AWS KMS**

## Why Correct?

KMS manages:

* Encryption keys
* Key rotation
* Key policies
* Access control for keys

---

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| B      | Permissions management |
| C      | Audit logging          |
| D      | DNS service            |

---

## Service: AWS Key Management Service (KMS)

### Definition

Managed encryption key service.

### Key Features

* Customer-managed keys
* Automatic key rotation
* Centralized key management

### Exam Traps

Encryption Keys = KMS

Encryption often uses KMS-managed keys.

### Memory Trick

KMS = Key Management Service

---

# Question 621 — Root User Security

## Question

A company wants to secure its AWS account root user.

Which action follows AWS best practices?

## Options

| Option | Action                                 |
| ------ | -------------------------------------- |
| A      | Create access keys for root user       |
| B      | Share root credentials                 |
| C      | Enable MFA on root user                |
| D      | Use root user for daily administration |

## Correct Answer

✅ **C. Enable MFA on Root User**

## Why Correct?

AWS recommends:

* MFA enabled on root account
* Minimal root account usage

---

## Why Others Are Wrong?

| Option | Reason                           |
| ------ | -------------------------------- |
| A      | Avoid root access keys           |
| B      | Never share credentials          |
| D      | Use IAM users for administration |

---

## Service: Root User Security

### Definition

Best practices for protecting the AWS account owner account.

### Key Features

* MFA enabled
* Emergency use only
* No shared access

### Exam Traps

Root User = Rarely Used

Root User ≠ Daily Administration

### Memory Trick

Root User = Break Glass Account

---

# Question 622 — AWS Config

## Question

Which AWS service helps evaluate AWS resources against compliance rules continuously?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | AWS Config |
| B      | CloudTrail |
| C      | Route 53   |
| D      | SNS        |

## Correct Answer

✅ **A. AWS Config**

## Why Correct?

Config continuously evaluates resources against compliance rules.

---

## Why Others Are Wrong?

| Option | Reason                |
| ------ | --------------------- |
| B      | Records activity logs |
| C      | DNS service           |
| D      | Notification service  |

---

## Service: AWS Config

### Definition

Compliance monitoring and configuration tracking service.

### Key Features

* Compliance rules
* Resource inventory
* Configuration history
* Continuous evaluation

### Exam Traps

Compliance Monitoring = Config

Audit Logs = CloudTrail

### Memory Trick

Config Checks Configuration

---

# Question 623 — AWS WAF

## Question

Which AWS service provides protection against SQL injection attacks?

## Options

| Option | Service          |
| ------ | ---------------- |
| A      | AWS Shield       |
| B      | AWS WAF          |
| C      | Amazon Inspector |
| D      | Amazon Macie     |

## Correct Answer

✅ **B. AWS WAF**

## Why Correct?

WAF filters malicious HTTP requests before they reach applications.

---

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | DDoS protection          |
| C      | Vulnerability scanning   |
| D      | Sensitive data discovery |

---

## Service: AWS WAF

### Definition

Web Application Firewall.

### Key Features

* SQL injection protection
* Cross-site scripting (XSS) protection
* HTTP request filtering

### Exam Traps

SQL Injection = WAF

XSS = WAF

DDoS = Shield

### Memory Trick

WAF Protects Websites

---

# Question 624 — AWS Security Hub

## Question

A company wants a centralized dashboard for security findings collected from multiple AWS security services.

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | AWS Security Hub   |
| B      | AWS CloudFormation |
| C      | AWS Lambda         |
| D      | Amazon Route 53    |

## Correct Answer

✅ **A. AWS Security Hub**

## Why Correct?

Security Hub aggregates findings from:

* GuardDuty
* Inspector
* Macie
* Partner security tools

---

## Why Others Are Wrong?

| Option | Reason                    |
| ------ | ------------------------- |
| B      | Infrastructure deployment |
| C      | Serverless compute        |
| D      | DNS service               |

---

## Service: AWS Security Hub

### Definition

Centralized security findings dashboard.

### Key Features

* Aggregated findings
* Compliance monitoring
* Security visibility
* Centralized reporting

### Exam Traps

Security Dashboard = Security Hub

Threat Detection = GuardDuty

### Memory Trick

Security Hub = Security Headquarters

---

# DOMAIN 2 MASTER CHEAT SHEET

## 🔥 Security Services Comparison

| Service             | Purpose                         |
| ------------------- | ------------------------------- |
| IAM                 | Permissions Management          |
| IAM Role            | Service Access                  |
| IAM Identity Center | Single Sign-On (SSO)            |
| Cognito             | Application User Authentication |
| CloudTrail          | Audit Logs                      |
| CloudWatch          | Monitoring                      |
| AWS Config          | Compliance Monitoring           |
| GuardDuty           | Threat Detection                |
| Inspector           | Vulnerability Scanning          |
| Macie               | Sensitive Data Discovery        |
| Security Hub        | Central Security Dashboard      |
| Shield              | DDoS Protection                 |
| WAF                 | SQL Injection & XSS Protection  |
| KMS                 | Encryption Keys                 |
| Artifact            | Compliance Reports              |

---

## 🔥 20 Facts You Must Memorize

| Concept                  | Answer              |
| ------------------------ | ------------------- |
| EC2 → S3 Access          | IAM Role            |
| API Logs                 | CloudTrail          |
| Metrics                  | CloudWatch          |
| Threat Detection         | GuardDuty           |
| Vulnerability Scan       | Inspector           |
| Sensitive Data Discovery | Macie               |
| Security Dashboard       | Security Hub        |
| SQL Injection Protection | WAF                 |
| DDoS Protection          | Shield              |
| Encryption Keys          | KMS                 |
| Compliance Reports       | Artifact            |
| Compliance Monitoring    | Config              |
| Single Sign-On           | IAM Identity Center |
| App Authentication       | Cognito             |
| Root User Security       | Enable MFA          |
| Security Principle       | Least Privilege     |
| Instance Firewall        | Security Group      |
| Subnet Firewall          | NACL                |
| Hardware Management      | AWS                 |
| IAM & Data Management    | Customer            |

---

## 🎯 Domain 2 Completion Status

### Identity & Access Management

✅ IAM

✅ IAM Roles

✅ IAM Identity Center

✅ Cognito

✅ MFA

✅ Least Privilege

---

### Shared Responsibility Model

✅ AWS Responsibilities

✅ Customer Responsibilities

---

### Monitoring & Compliance

✅ CloudTrail

✅ AWS Config

✅ Artifact

---

### Security Services

✅ GuardDuty

✅ Inspector

✅ Macie

✅ Security Hub

✅ WAF

✅ Shield

✅ KMS

---

### Network Security

✅ Security Groups

✅ Network ACLs

---

# DOMAIN 2 REVISION SUMMARY

```text
IAM                  → Permissions
IAM Role             → Service Access
IAM Identity Center  → SSO
Cognito              → App Authentication
CloudTrail           → Audit Logs
CloudWatch           → Monitoring
Config               → Compliance
GuardDuty            → Threat Detection
Inspector            → Vulnerability Scanning
Macie                → Sensitive Data Discovery
Security Hub         → Security Dashboard
WAF                  → SQL Injection / XSS
Shield               → DDoS Protection
KMS                  → Encryption Keys
Artifact             → Compliance Reports
Security Group       → Instance Firewall
NACL                 → Subnet Firewall
AWS                  → Hardware & Infrastructure
Customer             → IAM, Data, Access Control
```

**Domain 2 is effectively complete for CLF-C02 revision.**
