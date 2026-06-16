# DOMAIN 2 — BATCH 03

## Security & Compliance

> This batch covers some of the highest-frequency CLF-C02 security concepts.
>
> AWS repeatedly tests:
>
> * Shared Responsibility Model
> * MFA
> * Least Privilege
> * Macie
> * Security Hub
> * Shield Standard
> * IAM Security Best Practices
>
> These are often among the easiest exam questions if the core concepts are memorized.

---

# Question 5 — Shared Responsibility Model

## Question

According to the AWS Shared Responsibility Model, which task is the responsibility of the customer?

## Options

| Option | Responsibility                                     |
| ------ | -------------------------------------------------- |
| A      | Maintaining AWS data centers                       |
| B      | Managing physical hardware                         |
| C      | Configuring access permissions for DynamoDB tables |
| D      | Replacing failed hard drives                       |

## Correct Answer

✅ **C. Configuring Access Permissions for DynamoDB Tables**

## Why Correct?

Customers are responsible for:

* Data
* IAM permissions
* Access control
* Security configurations

---

## Why Others Are Wrong?

| Option | Reason             |
| ------ | ------------------ |
| A      | AWS responsibility |
| B      | AWS responsibility |
| D      | AWS responsibility |

---

## Service: Shared Responsibility Model

### Definition

AWS secures the cloud.

Customers secure what they place in the cloud.

### Key Principles

* AWS = Security **OF** the Cloud
* Customer = Security **IN** the Cloud

### Exam Traps

Data Permissions = Customer

Physical Infrastructure = AWS

### Memory Trick

AWS = OF the Cloud

Customer = IN the Cloud

---

# Question 482 — MFA Best Practices

## Question

Which security best practices should be followed for IAM users? (Choose two.)

## Options

| Option | Practice                         |
| ------ | -------------------------------- |
| A      | Use root user daily              |
| B      | Rotate credentials regularly     |
| C      | Share administrator credentials  |
| D      | Enable MFA                       |
| E      | Store access keys in source code |

## Correct Answers

✅ **B. Rotate Credentials Regularly**

✅ **D. Enable MFA**

## Why Correct?

AWS strongly recommends:

* Credential rotation
* Multi-Factor Authentication (MFA)

---

## Why Others Are Wrong?

| Option | Reason                             |
| ------ | ---------------------------------- |
| A      | Root user should rarely be used    |
| C      | Credentials should never be shared |
| E      | Major security risk                |

---

## Service: Multi-Factor Authentication (MFA)

### Definition

Adds an additional authentication factor beyond a password.

### Key Features

* Stronger security
* Protection against password theft
* Reduced account compromise risk

### Exam Traps

Extra Security Layer = MFA

### Memory Trick

Password + Device = MFA

---

# Question 483 — AWS Responsibility

## Question

Which activity is AWS responsible for under the Shared Responsibility Model?

## Options

| Option | Responsibility               |
| ------ | ---------------------------- |
| A      | Managing IAM users           |
| B      | Configuring security groups  |
| C      | Maintaining physical servers |
| D      | Encrypting customer data     |

## Correct Answer

✅ **C. Maintaining Physical Servers**

## Why Correct?

AWS owns and manages:

* Hardware
* Networking equipment
* Facilities
* Physical security

---

## Why Others Are Wrong?

| Option | Reason                                 |
| ------ | -------------------------------------- |
| A      | Customer responsibility                |
| B      | Customer responsibility                |
| D      | Customer controls encryption decisions |

---

## Service: AWS Responsibility

### Definition

Security OF the Cloud.

### Key Features

* Physical security
* Infrastructure management
* Global network operations

### Exam Traps

Hardware = AWS

Permissions = Customer

### Memory Trick

AWS Owns the Building.

---

# Question 610 — Principle of Least Privilege

## Question

A company wants to follow the principle of least privilege.

Which IAM practice supports this principle?

## Options

| Option | Practice                                         |
| ------ | ------------------------------------------------ |
| A      | Grant AdministratorAccess to all users           |
| B      | Give permissions only required for job functions |
| C      | Share IAM accounts among teams                   |
| D      | Use root user for applications                   |

## Correct Answer

✅ **B. Give Permissions Only Required for Job Functions**

## Why Correct?

Least privilege means users receive only the permissions necessary to perform their jobs.

---

## Why Others Are Wrong?

| Option | Reason                                          |
| ------ | ----------------------------------------------- |
| A      | Excessive permissions                           |
| C      | Poor security practice                          |
| D      | Root user should never be used for applications |

---

## Service: Least Privilege

### Definition

Grant only the minimum permissions required.

### Key Features

* Reduced attack surface
* Improved security
* Better compliance

### Exam Traps

Minimum Permissions = Least Privilege

### Memory Trick

Need-to-Know Access Only.

---

# Question 611 — Amazon Macie

## Question

Which AWS service helps customers discover sensitive data stored in Amazon S3?

## Options

| Option | Service          |
| ------ | ---------------- |
| A      | Amazon Macie     |
| B      | Amazon Inspector |
| C      | AWS Shield       |
| D      | Amazon Cognito   |

## Correct Answer

✅ **A. Amazon Macie**

## Why Correct?

Macie identifies:

* Personally Identifiable Information (PII)
* Sensitive data
* Data exposure risks

within Amazon S3.

---

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| B      | Vulnerability scanning |
| C      | DDoS protection        |
| D      | Authentication service |

---

## Service: Amazon Macie

### Definition

Sensitive data discovery and classification service.

### Key Features

* PII detection
* Data classification
* S3 analysis
* Security findings

### Exam Traps

Sensitive Data in S3 = Macie

### Memory Trick

Macie Searches Your S3 Buckets.

### Compare With

| Service   | Purpose                  |
| --------- | ------------------------ |
| Macie     | Sensitive Data Discovery |
| Inspector | Vulnerability Scanning   |
| GuardDuty | Threat Detection         |

---

# Question 612 — AWS Security Hub

## Question

Which AWS service provides centralized findings from multiple AWS security services?

## Options

| Option | Service          |
| ------ | ---------------- |
| A      | AWS Security Hub |
| B      | AWS CloudTrail   |
| C      | Amazon Route 53  |
| D      | Amazon Athena    |

## Correct Answer

✅ **A. AWS Security Hub**

## Why Correct?

Security Hub aggregates findings from:

* GuardDuty
* Inspector
* Macie
* AWS Partner Tools

into one dashboard.

---

## Why Others Are Wrong?

| Option | Reason             |
| ------ | ------------------ |
| B      | Audit logging only |
| C      | DNS service        |
| D      | Query service      |

---

## Service: AWS Security Hub

### Definition

Centralized security dashboard and findings aggregator.

### Key Features

* Aggregates findings
* Security visibility
* Compliance monitoring
* Centralized reporting

### Exam Traps

Single Security Dashboard = Security Hub

### Memory Trick

Security Hub = Security Control Center.

### Compare With

| Service      | Purpose                  |
| ------------ | ------------------------ |
| Security Hub | Central Dashboard        |
| GuardDuty    | Threat Detection         |
| Inspector    | Vulnerability Assessment |
| Macie        | Sensitive Data Discovery |

---

# Question 614 — AWS Shield Standard

## Question

Which AWS service can protect applications against DDoS attacks automatically at no additional cost?

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | AWS Shield Standard |
| B      | AWS WAF             |
| C      | AWS Config          |
| D      | Amazon Inspector    |

## Correct Answer

✅ **A. AWS Shield Standard**

## Why Correct?

Shield Standard is included automatically with AWS services and provides baseline DDoS protection.

---

## Why Others Are Wrong?

| Option | Reason                       |
| ------ | ---------------------------- |
| B      | Protects against web attacks |
| C      | Configuration tracking       |
| D      | Vulnerability scanning       |

---

## Service: AWS Shield Standard

### Definition

Basic DDoS protection included with AWS services.

### Key Features

* Automatic protection
* No additional cost
* Layer 3/Layer 4 protection

### Exam Traps

DDoS = Shield

SQL Injection = WAF

### Memory Trick

Shield Blocks Attack Traffic.

### Compare With

| Service | Purpose                    |
| ------- | -------------------------- |
| Shield  | DDoS Protection            |
| WAF     | Web Application Protection |

---

# Batch 03 Cheat Sheet

## 🔥 Top Services

* Amazon Macie
* AWS Security Hub
* MFA
* AWS Shield Standard
* Least Privilege

---

## 🔥 Top Facts To Memorize

| Concept                     | Answer              |
| --------------------------- | ------------------- |
| Sensitive S3 Data           | Macie               |
| Security Findings Dashboard | Security Hub        |
| DDoS Protection             | Shield              |
| SQL Injection Protection    | WAF                 |
| Threat Detection            | GuardDuty           |
| Vulnerability Scanning      | Inspector           |
| Audit Logs                  | CloudTrail          |
| Compliance Tracking         | AWS Config          |
| App Users                   | Cognito             |
| Least Privilege             | Minimum Permissions |

---

## 🔥 Security Mega Comparison Table

| Service             | Purpose                    |
| ------------------- | -------------------------- |
| Inspector           | Vulnerability Scanning     |
| GuardDuty           | Threat Detection           |
| Macie               | Sensitive Data Discovery   |
| Security Hub        | Security Dashboard         |
| CloudTrail          | Audit Logs                 |
| AWS Config          | Compliance Tracking        |
| Shield              | DDoS Protection            |
| WAF                 | Web Attack Protection      |
| Cognito             | Application Authentication |
| IAM Identity Center | Single Sign-On             |

---

## 🔥 Most Likely Questions To Reappear

1. GuardDuty vs Inspector
2. Macie vs Security Hub
3. WAF vs Shield
4. CloudTrail vs Config
5. IAM vs Cognito
6. Least Privilege Questions
7. Shared Responsibility Model

---

# Batch 03 Summary

```text id="k4f8xp"
Macie          → Sensitive Data Discovery
Security Hub   → Central Security Dashboard
MFA            → Extra Authentication Layer
Shield         → DDoS Protection
WAF            → SQL Injection / XSS Protection
GuardDuty      → Threat Detection
Inspector      → Vulnerability Scanning
CloudTrail     → Audit Logs
Config         → Compliance Monitoring
Least Privilege→ Minimum Required Permissions
```
