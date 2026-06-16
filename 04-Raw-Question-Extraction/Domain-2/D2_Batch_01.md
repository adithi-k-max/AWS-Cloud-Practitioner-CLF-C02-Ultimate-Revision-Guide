# DOMAIN 2 — BATCH 01

## Security & Compliance

> **Important for CLF-C02**
>
> Domain 2 contributes approximately **30% of the exam** (about 19–20 questions).
>
> AWS repeatedly tests:
>
> * IAM
> * MFA
> * IAM Roles
> * Security Groups
> * Network ACLs
> * AWS WAF
> * AWS Shield
> * GuardDuty
> * Inspector
> * CloudTrail
> * AWS KMS
> * AWS Artifact
> * Shared Responsibility Model
>
> Mastering these topics can help secure a large portion of the exam score.

---

# Question 2 — Amazon Inspector

## Question

A company has deployed applications on Amazon EC2 instances.

The company needs to assess application vulnerabilities and identify deployments that do not meet security best practices.

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | AWS Trusted Advisor |
| B      | Amazon Inspector    |
| C      | AWS Config          |
| D      | Amazon GuardDuty    |

## Correct Answer

✅ **B. Amazon Inspector**

## Why Correct?

### Keywords

* Vulnerabilities
* EC2
* Security assessment

Amazon Inspector scans workloads and identifies vulnerabilities.

---

## Why Others Are Wrong?

| Option | Reason                                               |
| ------ | ---------------------------------------------------- |
| A      | Provides recommendations, not vulnerability scanning |
| C      | Tracks configuration compliance                      |
| D      | Detects threats, not vulnerabilities                 |

---

## Service: Amazon Inspector

### Definition

Automated vulnerability management service.

### Key Features

* Vulnerability scanning
* EC2 scanning
* ECR scanning
* Lambda scanning

### Exam Traps

Vulnerability Scan = Inspector

Threat Detection = GuardDuty

### Memory Trick

Inspector Inspects Your Systems.

### Compare With

| Service   | Purpose                  |
| --------- | ------------------------ |
| Inspector | Vulnerability Assessment |
| GuardDuty | Threat Detection         |

---

# Question 289 — Security Groups

## Question

Which task can a company perform by using Security Groups?

## Options

| Option | Task                                                         |
| ------ | ------------------------------------------------------------ |
| A      | Allow access to an EC2 instance through only a specific port |
| B      | Deny access to malicious IP addresses at subnet level        |
| C      | Protect CloudFront cached data                               |
| D      | Apply a stateless firewall                                   |

## Correct Answer

✅ **A. Allow Access Through Specific Ports**

## Why Correct?

Security Groups control inbound and outbound traffic for EC2 instances.

---

## Why Others Are Wrong?

| Option | Reason                                     |
| ------ | ------------------------------------------ |
| B      | Network ACL handles subnet-level filtering |
| C      | Not a Security Group function              |
| D      | Security Groups are stateful               |

---

## Service: Security Group

### Definition

Instance-level virtual firewall.

### Key Features

* Stateful
* Allow rules only
* EC2 protection

### Exam Traps

Instance Firewall = Security Group

Subnet Firewall = NACL

### Memory Trick

Security Group Protects the Server.

### Compare With

| Feature        | Scope    |
| -------------- | -------- |
| Security Group | Instance |
| NACL           | Subnet   |

---

# Question 291 — Network ACL

## Question

Which features belong to Network ACLs? (Choose two.)

## Options

| Option | Feature                   |
| ------ | ------------------------- |
| A      | Stateless                 |
| B      | Stateful                  |
| C      | Evaluate all rules        |
| D      | Process rules in order    |
| E      | Operate at instance level |

## Correct Answers

✅ **A. Stateless**

✅ **D. Process Rules in Order**

## Why Correct?

Network ACLs:

* Are stateless
* Process rules sequentially
* Stop at first matching rule

---

## Why Others Are Wrong?

| Option | Reason                            |
| ------ | --------------------------------- |
| B      | Security Groups are stateful      |
| C      | NACLs stop at first matching rule |
| E      | NACLs operate at subnet level     |

---

## Service: Network ACL

### Definition

Subnet-level firewall.

### Key Features

* Stateless
* Allow rules
* Deny rules
* Rule ordering

### Exam Traps

Subnet = NACL

Instance = Security Group

### Memory Trick

NACL = Neighborhood Firewall.

### Compare With

| Feature        | Scope    |
| -------------- | -------- |
| Security Group | Instance |
| NACL           | Subnet   |

---

# Question 293 — Shared Responsibility Model

## Question

According to the AWS Shared Responsibility Model, the customer is responsible for applying patches to which service?

## Options

| Option | Service       |
| ------ | ------------- |
| A      | DynamoDB      |
| B      | EC2 Instances |
| C      | Amazon RDS    |
| D      | Amazon S3     |

## Correct Answer

✅ **B. EC2 Instances**

## Why Correct?

Customers manage the operating system running on EC2 instances.

Customers are responsible for patching the OS.

---

## Why Others Are Wrong?

| Option | Reason                          |
| ------ | ------------------------------- |
| A      | Fully managed by AWS            |
| C      | AWS manages underlying patching |
| D      | Fully managed by AWS            |

---

## Service: Shared Responsibility Model

### Definition

AWS secures the cloud.

Customers secure what they place in the cloud.

### Exam Traps

EC2 OS = Customer Responsibility

Managed Services = AWS Responsibility

### Memory Trick

EC2 = You Patch It.

---

# Question 479 — AWS Artifact

## Question

Which AWS service gives users on-demand access to AWS compliance reports?

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | AWS Config          |
| B      | Amazon GuardDuty    |
| C      | AWS Trusted Advisor |
| D      | AWS Artifact        |

## Correct Answer

✅ **D. AWS Artifact**

## Why Correct?

Artifact contains:

* SOC Reports
* Compliance Reports
* Security Certifications

---

## Why Others Are Wrong?

| Option | Reason                        |
| ------ | ----------------------------- |
| A      | Compliance monitoring         |
| B      | Threat detection              |
| C      | Best-practice recommendations |

---

## Service: AWS Artifact

### Definition

Self-service portal for compliance reports and agreements.

### Key Features

* Audit reports
* Compliance documentation
* Security certifications

### Exam Traps

Compliance Documents = Artifact

### Memory Trick

Artifact = AWS Audit Documents.

---

# Question 482 — IAM Best Practices

## Question

Which IAM best practices are recommended? (Choose two.)

## Options

| Option | Practice                 |
| ------ | ------------------------ |
| A      | Use Root User daily      |
| B      | Store access keys on EC2 |
| C      | Rotate credentials       |
| D      | Shared admin keys        |
| E      | Enable MFA               |

## Correct Answers

✅ **C. Rotate Credentials**

✅ **E. Enable MFA**

## Why Correct?

AWS recommends:

* Credential rotation
* Multi-Factor Authentication (MFA)

---

## Why Others Are Wrong?

| Option | Reason                                          |
| ------ | ----------------------------------------------- |
| A      | Root user should only be used for special tasks |
| B      | IAM Roles should be used instead                |
| D      | Credentials should never be shared              |

---

## Service: IAM Best Practices

### Definition

Recommended security practices for IAM users and accounts.

### Key Features

* MFA
* Least privilege
* Credential rotation
* Strong authentication

### Exam Traps

Root User = Emergency Use Only

### Memory Trick

MFA + Rotation = Secure IAM.

---

# Question 483 — AWS Responsibility

## Question

Which option is AWS responsible for under the Shared Responsibility Model?

## Options

| Option | Responsibility                 |
| ------ | ------------------------------ |
| A      | Network firewall configuration |
| B      | Client-side encryption         |
| C      | User permissions               |
| D      | Hardware and infrastructure    |

## Correct Answer

✅ **D. Hardware and Infrastructure**

## Why Correct?

AWS owns and manages:

* Data centers
* Physical servers
* Networking hardware
* Facilities

---

## Why Others Are Wrong?

| Option | Reason                  |
| ------ | ----------------------- |
| A      | Customer responsibility |
| B      | Customer responsibility |
| C      | Customer responsibility |

---

## Service: AWS Responsibility

### Definition

Security OF the Cloud.

### Key Features

* Hardware
* Facilities
* Physical networking
* Infrastructure

### Exam Traps

Physical Security = AWS

User Security = Customer

### Memory Trick

AWS Owns the Building.

---

# Question 603 — Amazon GuardDuty

## Question

What is the primary use case for Amazon GuardDuty?

## Options

| Option | Purpose                  |
| ------ | ------------------------ |
| A      | DDoS Prevention          |
| B      | SQL Injection Protection |
| C      | Threat Detection         |
| D      | Resource Provisioning    |

## Correct Answer

✅ **C. Threat Detection**

## Why Correct?

GuardDuty continuously analyzes:

* VPC Flow Logs
* CloudTrail Logs
* DNS Logs

to identify threats.

---

## Why Others Are Wrong?

| Option | Reason                             |
| ------ | ---------------------------------- |
| A      | AWS Shield handles DDoS protection |
| B      | AWS WAF helps mitigate web attacks |
| D      | Not a provisioning service         |

---

## Service: Amazon GuardDuty

### Definition

Intelligent threat detection service.

### Key Features

* Threat detection
* Continuous monitoring
* ML-based analysis
* Security findings

### Exam Traps

Threat Detection = GuardDuty

Vulnerability Scan = Inspector

### Memory Trick

GuardDuty Guards the Perimeter.

### Compare With

| Service   | Purpose                    |
| --------- | -------------------------- |
| GuardDuty | Threat Detection           |
| Inspector | Vulnerability Scanning     |
| Shield    | DDoS Protection            |
| WAF       | Web Application Protection |

---

# Batch 01 Cheat Sheet

## 🔥 Top Services

* Amazon Inspector
* Amazon GuardDuty
* Security Groups
* Network ACLs
* AWS Artifact
* IAM
* MFA

---

## 🔥 Top Facts To Memorize

| Concept              | Answer                  |
| -------------------- | ----------------------- |
| Vulnerability Scan   | Inspector               |
| Threat Detection     | GuardDuty               |
| Instance Firewall    | Security Group          |
| Subnet Firewall      | NACL                    |
| Compliance Reports   | Artifact                |
| Enable MFA           | IAM Best Practice       |
| Rotate Credentials   | IAM Best Practice       |
| AWS Manages Hardware | AWS Responsibility      |
| Customer Patches EC2 | Customer Responsibility |
| Root User            | Emergency Use Only      |

---

## 🔥 Most Likely Questions to Reappear

1. GuardDuty vs Inspector
2. Security Group vs NACL
3. AWS vs Customer Responsibility
4. MFA Best Practices
5. Artifact vs Config

---

# Batch 01 Summary

```text
Inspector       → Vulnerability Scanning
GuardDuty       → Threat Detection
Security Group  → Instance Firewall
NACL            → Subnet Firewall
Artifact        → Compliance Reports
MFA             → Security Best Practice
EC2 Patching    → Customer Responsibility
Hardware        → AWS Responsibility
```
