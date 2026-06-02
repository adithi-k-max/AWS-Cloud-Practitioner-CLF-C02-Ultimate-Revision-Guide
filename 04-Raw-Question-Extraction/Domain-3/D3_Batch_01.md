# DOMAIN 3 — BATCH 01
## Cloud Technology & Services

---

# Question 1 — Amazon Snowball Edge

## Question

A company plans to use an Amazon Snowball Edge device to transfer files to the AWS Cloud.

Which activities related to a Snowball Edge device are available to the company at no cost?

## Options

| Option | Answer |
|----------|----------|
| A | Use of the Snowball Edge appliance for a 10-day period |
| B | Transfer of data out of Amazon S3 and to the Snowball Edge appliance |
| C | Transfer of data from the Snowball Edge appliance into Amazon S3 |
| D | Daily use of the Snowball Edge appliance after 10 days |

## Correct Answer

✅ **C. Transfer of data from the Snowball Edge appliance into Amazon S3**

## Why Correct?

AWS does not charge for importing data into AWS via Snowball.

### Exam Keywords

- Snowball
- Import Data
- AWS

### Exam Mapping

```text
Snowball → Import Data into AWS
```

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Device usage incurs charges |
| B | Exporting data out of AWS is chargeable |
| D | Additional usage beyond allotted period incurs charges |

---

## Service Deep Dive — Amazon Snowball Edge

### Definition

Physical device used for large-scale offline data migration.

### Key Features

- Petabyte-scale transfer
- Offline migration
- Edge computing
- Secure transport

### Exam Traps

❌ Snowball ≠ Storage

❌ Snowball ≠ Backup

✅ Snowball = Data Transfer

### Memory Trick

📦 Too much data for internet?

➡ Ship a Snowball.

### Comparison

| Service | Purpose |
|----------|----------|
| Snowball | Offline Transfer |
| DataSync | Online Transfer |

---

# Question 2 — Amazon Inspector

## Question

A company has deployed applications on Amazon EC2 instances.

The company needs to assess application vulnerabilities and identify infrastructure deployments that do not meet best practices.

Which AWS service can the company use?

## Options

| Option | Answer |
|----------|----------|
| A | AWS Trusted Advisor |
| B | Amazon Inspector |
| C | AWS Config |
| D | Amazon GuardDuty |

## Correct Answer

✅ **B. Amazon Inspector**

## Why Correct?

Amazon Inspector performs:

- Vulnerability scanning
- Security assessments
- EC2 workload analysis

### Keywords

- Vulnerabilities
- Assessment
- EC2

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Trusted Advisor provides recommendations only |
| C | AWS Config tracks configurations |
| D | GuardDuty performs threat detection |

---

## Service Deep Dive — Amazon Inspector

### Definition

AWS vulnerability assessment service.

### Key Features

- EC2 scanning
- Container scanning
- CVE detection

### Exam Traps

Inspector vs GuardDuty

### Memory Trick

```text
Inspector → Finds Weaknesses

GuardDuty → Finds Attackers
```

### Comparison

| Service | Purpose |
|----------|----------|
| Inspector | Vulnerability Assessment |
| GuardDuty | Threat Detection |
| Security Hub | Security Dashboard |

---

# Question 3 — AWS Storage Gateway

## Question

A company has centralized users with large file storage requirements that exceed on-premises storage.

The company wants local performance while extending storage into AWS.

## Options

| Option | Answer |
|----------|----------|
| A | S3 bucket per user |
| B | AWS Storage Gateway File Gateway |
| C | WorkSpaces + WorkDocs |
| D | EC2 + EBS |

## Correct Answer

✅ **B. AWS Storage Gateway File Gateway**

## Why Correct?

### Keywords

- On-premises
- Local performance
- Extend storage to cloud

Storage Gateway is designed specifically for hybrid storage.

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Not operationally efficient |
| C | Changes user environment unnecessarily |
| D | Difficult to scale and manage |

---

## Service Deep Dive — AWS Storage Gateway

### Definition

Hybrid cloud storage bridge.

### Key Features

- Local access
- Cloud storage
- File Gateway

### Exam Trap

```text
Hybrid Environment → Storage Gateway
```

### Memory Trick

Gateway = Bridge

### Comparison

| Service | Purpose |
|----------|----------|
| Storage Gateway | Hybrid Storage |
| S3 | Cloud Storage |

---

# Question 4 — IAM Role

## Question

According to AWS security best practices, how should an EC2 instance be given access to an S3 bucket?

## Options

| Option | Answer |
|----------|----------|
| A | Hardcode access keys |
| B | Store keys in text file |
| C | Have EC2 assume a role |
| D | Open bucket to all services |

## Correct Answer

✅ **C. Have EC2 assume a role**

## Why Correct?

AWS best practice:

```text
EC2 → IAM Role → S3
```

No credentials should be stored on the instance.

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Security risk |
| B | Security risk |
| D | Violates least privilege principle |

---

## Service Deep Dive — IAM Role

### Definition

Temporary AWS permissions assigned to AWS services.

### Key Features

- Secure credentials
- EC2 access
- Cross-account access

### Exam Trap

```text
EC2 Accessing AWS Service
→ IAM Role
```

### Memory Trick

```text
Humans → IAM Users

Services → IAM Roles
```

### Comparison

| Service | Purpose |
|----------|----------|
| IAM User | Human |
| IAM Role | Service |

---

# Question 7 — AWS Fargate

## Question

A company manages Docker containers on EC2.

The company wants AWS to manage cluster sizing, scheduling, and maintenance.

## Options

| Option | Answer |
|----------|----------|
| A | Lambda |
| B | RDS |
| C | AWS Fargate |
| D | Athena |

## Correct Answer

✅ **C. AWS Fargate**

## Why Correct?

### Keywords

- Docker
- Containers
- No infrastructure management

Fargate provides serverless containers.

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Functions, not containers |
| B | Database service |
| D | Query service |

---

## Service Deep Dive — AWS Fargate

### Definition

Serverless compute engine for containers.

### Key Features

- No server management
- ECS integration
- EKS integration

### Exam Trap

```text
Docker + No Servers
→ Fargate
```

### Memory Trick

```text
Lambda → Functions

Fargate → Containers
```

---

# Batch 01 Cheat Sheet

## 🔥 Top Services

| Service | Core Concept |
|----------|----------|
| Snowball Edge | Offline Migration |
| Amazon Inspector | Vulnerability Scanning |
| Storage Gateway | Hybrid Storage |
| IAM Role | Service Permissions |
| AWS Fargate | Serverless Containers |

---

## 🔥 Top Facts To Memorize

| Concept | Remember |
|----------|----------|
| Snowball | Offline Data Transfer |
| Inspector | Vulnerability Assessment |
| Storage Gateway | Hybrid Storage |
| IAM Role | EC2 → AWS Access |
| Fargate | Containers Without Servers |

---

## 🔥 Most Repeated Exam Traps

| Wrong Answer | Correct Answer |
|----------|----------|
| GuardDuty | Inspector |
| IAM User | IAM Role |
| S3 | Storage Gateway |
| Lambda | Fargate |

---

## 🔥 Questions Likely To Reappear

1. EC2 → S3 Access
2. Vulnerability Scanning
3. Hybrid Storage
4. Docker Container Management
5. Data Migration Services

---

# Batch 01 Summary

```text
Snowball      → Offline Transfer
Inspector     → Vulnerability Assessment
StorageGateway→ Hybrid Storage
IAM Role      → EC2 to AWS Access
Fargate       → Serverless Containers
```
