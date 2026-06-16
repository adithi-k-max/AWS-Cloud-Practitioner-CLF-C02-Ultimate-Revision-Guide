# DOMAIN 3 — BATCH 11

## Cloud Technology & Services

---

# Question 290 — EC2 Accelerated Computing Instances

## Question

A company plans to run a compute-intensive workload that uses graphics processing units (GPUs).

Which Amazon EC2 instance type should the company use?

## Options

| Option | Instance Type         |
| ------ | --------------------- |
| A      | Accelerated Computing |
| B      | Compute Optimized     |
| C      | Storage Optimized     |
| D      | General Purpose       |

## Correct Answer

✅ **A. Accelerated Computing**

## Why Correct?

### Keywords

* GPU
* Graphics processing
* Machine learning
* High-performance computing

Accelerated Computing instances provide GPU hardware for specialized workloads.

---

## Why Others Are Wrong?

| Option | Reason                                   |
| ------ | ---------------------------------------- |
| B      | Optimized for CPU workloads, not GPU     |
| C      | Designed for storage-intensive workloads |
| D      | Balanced resources, not GPU specialized  |

---

## Service: EC2 Accelerated Computing

### Definition

EC2 instances designed specifically for GPU-based workloads.

### Key Features

* GPU support
* Machine learning
* Graphics rendering
* High-performance computing (HPC)

### Exam Traps

GPU = Accelerated Computing

### Memory Trick

Accelerated = GPU Power.

### Compare With

| Instance Type         | Best For                       |
| --------------------- | ------------------------------ |
| Accelerated Computing | GPU Workloads                  |
| Compute Optimized     | CPU Workloads                  |
| Storage Optimized     | Storage Intensive Applications |
| General Purpose       | Balanced Workloads             |

---

# Question 291 — Network ACL Features

## Question

Which of the following are features of Network ACLs? (Choose two.)

## Options

| Option | Feature                                                   |
| ------ | --------------------------------------------------------- |
| A      | Stateless                                                 |
| B      | Stateful                                                  |
| C      | Evaluate all rules before allowing traffic                |
| D      | Process rules in order starting with lowest numbered rule |
| E      | Operate at instance level                                 |

## Correct Answers

✅ **A. Stateless**

✅ **D. Process Rules in Order**

## Why Correct?

Network ACLs:

* Are stateless
* Process rules sequentially
* Stop processing when a matching rule is found

---

## Why Others Are Wrong?

| Option | Reason                                |
| ------ | ------------------------------------- |
| B      | Security Groups are stateful          |
| C      | NACLs stop at the first matching rule |
| E      | NACLs operate at subnet level         |

---

## Service: Network ACL

### Definition

Subnet-level virtual firewall.

### Key Features

* Stateless
* Allow rules
* Deny rules
* Rule order matters

### Exam Traps

Subnet = NACL

Instance = Security Group

Stateless = NACL

Stateful = Security Group

### Memory Trick

NACL = Neighborhood Firewall.

### Compare With

| Service        | Scope    |
| -------------- | -------- |
| Security Group | Instance |
| Network ACL    | Subnet   |

---

# Question 472 — Multi-Region Architecture

## Question

A company wants its Amazon EC2 instances to operate in a highly available environment even if a natural disaster occurs in a geographic area.

## Options

| Option | Solution                                                              |
| ------ | --------------------------------------------------------------------- |
| A      | Use EC2 instances in multiple AWS Regions                             |
| B      | Use EC2 instances in multiple Edge Locations                          |
| C      | Use EC2 instances in the same Availability Zone but different Regions |
| D      | Use CloudFront with EC2                                               |

## Correct Answer

✅ **A. Use EC2 Instances in Multiple AWS Regions**

## Why Correct?

### Keywords

* Natural disaster
* Geographic failure
* Disaster recovery

A regional disaster requires infrastructure in another AWS Region.

---

## Why Others Are Wrong?

| Option | Reason                                         |
| ------ | ---------------------------------------------- |
| B      | Edge Locations are CDN infrastructure          |
| C      | Technically incorrect wording                  |
| D      | CloudFront is not a disaster recovery solution |

---

## Service: Multi-Region Architecture

### Definition

Deploying workloads across multiple AWS Regions.

### Key Features

* Disaster recovery
* High availability
* Geographic redundancy
* Business continuity

### Exam Traps

Natural Disaster = Multi-Region

Availability Zone Failure = Multi-AZ

### Memory Trick

Region Fails → Use Another Region.

### Compare With

| Architecture | Protection Against |
| ------------ | ------------------ |
| Multi-AZ     | AZ Failure         |
| Multi-Region | Regional Disaster  |

---

# Question 473 — Amazon EFS

## Question

Which AWS service allows file sharing between multiple Amazon EC2 instances?

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | AWS Direct Connect |
| B      | AWS Snowball Edge  |
| C      | AWS Backup         |
| D      | Amazon EFS         |

## Correct Answer

✅ **D. Amazon EFS**

## Why Correct?

Amazon EFS is a shared file system that supports simultaneous access from multiple EC2 instances.

---

## Why Others Are Wrong?

| Option | Reason                |
| ------ | --------------------- |
| A      | Networking service    |
| B      | Data migration device |
| C      | Backup service        |

---

## Service: Amazon EFS

### Definition

Managed shared file storage service.

### Key Features

* Multiple EC2 access
* Linux file system
* Automatic scaling
* Shared storage

### Exam Traps

Shared Files = EFS

Single EC2 Disk = EBS

### Memory Trick

EFS = Elastic File System.

### Compare With

| Service | Storage Type        |
| ------- | ------------------- |
| EBS     | Block Storage       |
| EFS     | Shared File Storage |
| S3      | Object Storage      |

---

# Question 476 — Amazon Route 53

## Question

A company is migrating its public website to AWS. The company wants to host the domain name for the website on AWS.

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | AWS Lambda         |
| B      | Amazon Route 53    |
| C      | Amazon CloudFront  |
| D      | AWS Direct Connect |

## Correct Answer

✅ **B. Amazon Route 53**

## Why Correct?

Route 53 provides:

* DNS services
* Domain registration
* Routing policies

---

## Why Others Are Wrong?

| Option | Reason             |
| ------ | ------------------ |
| A      | Compute service    |
| C      | CDN service        |
| D      | Networking service |

---

## Service: Amazon Route 53

### Definition

AWS DNS and domain registration service.

### Key Features

* DNS management
* Domain registration
* Health checks
* Traffic routing

### Exam Traps

Domain Name = Route 53

DNS = Route 53

### Memory Trick

Route Traffic → Route 53.

### Compare With

| Service        | Purpose            |
| -------------- | ------------------ |
| Route 53       | DNS                |
| CloudFront     | Content Delivery   |
| Direct Connect | Private Networking |

---

# Domain 3 Coverage Status

## Coverage Confidence

Based on all extracted batches and cross-checking against the visible sections of the dump:

### ✅ Core Services

* EC2
* Lambda
* ECS
* EKS
* Fargate
* Elastic Beanstalk

### ✅ Storage Services

* S3
* EBS
* EFS
* Glacier
* Storage Gateway
* Intelligent-Tiering

### ✅ Networking Services

* Route 53
* Direct Connect
* VPN
* Transit Gateway
* Security Groups
* Network ACLs
* Internet Gateway

### ✅ Databases

* RDS
* Aurora
* DynamoDB
* Neptune
* Redshift

### ✅ Analytics & Data

* Athena
* Kinesis
* QuickSight
* Glue

### ✅ Containers

* ECS
* EKS
* Fargate

### ✅ Monitoring & Management

* CloudWatch
* CloudTrail
* CloudFormation
* Systems Manager

### ✅ Migration Services

* DMS
* SCT
* DataSync

### ✅ Messaging Services

* SNS
* SQS

### ✅ End User & AI Services

* Polly
* Lex
* WorkSpaces
* AppStream 2.0

---

# Domain 3 Final Revision Summary

## 🔥 Highest Frequency Exam Topics

| Topic                  | Service             |
| ---------------------- | ------------------- |
| Serverless Compute     | Lambda              |
| Containers             | ECS / EKS / Fargate |
| Object Storage         | S3                  |
| Shared File Storage    | EFS                 |
| EC2 Storage            | EBS                 |
| DNS                    | Route 53            |
| Monitoring             | CloudWatch          |
| Notifications          | SNS                 |
| Queueing               | SQS                 |
| Data Warehouse         | Redshift            |
| NoSQL                  | DynamoDB            |
| Relational Database    | RDS                 |
| Graph Database         | Neptune             |
| CDN                    | CloudFront          |
| Infrastructure as Code | CloudFormation      |

---

## 🎯 Domain 3 Completion Status

**Coverage Confidence: ~100% of visible Domain 3 questions from the dump**

All major AWS Cloud Technology & Services concepts appearing throughout the dump have been extracted, categorized, and documented.
