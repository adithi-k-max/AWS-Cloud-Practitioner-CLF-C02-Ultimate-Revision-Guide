# DOMAIN 3 — BATCH 10

## Cloud Technology & Services

---

# Question 478 — AWS DMS & AWS Schema Conversion Tool

## Question

Which combination of AWS services can be used to move a commercial relational database to an Amazon-managed open-source database? (Choose two.)

## Options

| Option | Service                                  |
| ------ | ---------------------------------------- |
| A      | AWS Database Migration Service (AWS DMS) |
| B      | AWS SDKs                                 |
| C      | AWS Schema Conversion Tool (SCT)         |
| D      | AWS Systems Manager                      |
| E      | Amazon EMR                               |

## Correct Answers

✅ **AWS Database Migration Service (AWS DMS)**

✅ **AWS Schema Conversion Tool (SCT)**

## Why Correct?

Database migration usually requires two steps:

### Step 1 — Convert Schema

Use AWS Schema Conversion Tool (SCT)

### Step 2 — Move Data

Use AWS Database Migration Service (DMS)

---

## Why Others Are Wrong?

| Option | Reason                        |
| ------ | ----------------------------- |
| B      | Programming libraries only    |
| D      | Operations management service |
| E      | Big data analytics platform   |

---

## Service: AWS Database Migration Service (DMS)

### Definition

Service used to migrate databases into AWS.

### Key Features

* Minimal downtime
* Continuous replication
* Homogeneous migrations
* Heterogeneous migrations

### Memory Trick

DMS = Data Moves Smoothly.

---

## Service: AWS Schema Conversion Tool (SCT)

### Definition

Converts database schemas to compatible target database engines.

### Key Features

* Oracle → PostgreSQL
* SQL Server → Aurora
* Schema conversion automation

### Exam Traps

Convert Schema = SCT

Move Data = DMS

### Compare With

| Task           | Service |
| -------------- | ------- |
| Convert Schema | SCT     |
| Migrate Data   | DMS     |

---

# Question 590 — AWS Fargate

## Question

A company wants to run containers without provisioning or managing servers.

## Options

| Option | Service               |
| ------ | --------------------- |
| A      | AWS Lambda            |
| B      | AWS Fargate           |
| C      | Amazon EC2            |
| D      | AWS Elastic Beanstalk |

## Correct Answer

✅ **B. AWS Fargate**

## Why Correct?

### Keywords

* Containers
* No servers

Fargate is a serverless compute engine for containers.

---

## Why Others Are Wrong?

| Option | Reason                                  |
| ------ | --------------------------------------- |
| A      | Runs functions, not container workloads |
| C      | Requires server management              |
| D      | Still provisions infrastructure         |

---

## Service: AWS Fargate

### Definition

Serverless compute engine for containers.

### Key Features

* ECS integration
* EKS integration
* No infrastructure management
* Automatic scaling

### Exam Traps

Containers + No Servers = Fargate

Containers = ECS

Kubernetes = EKS

Serverless Containers = Fargate

### Memory Trick

Fargate = Forget Servers.

### Compare With

| Service | Purpose               |
| ------- | --------------------- |
| ECS     | Container Platform    |
| EKS     | Kubernetes Platform   |
| Fargate | Serverless Containers |

---

# Question 607 — Amazon S3 Standard-IA

## Question

A company needs to store audio files in S3.

Files are rarely accessed but must be available immediately when needed.

## Options

| Option | Storage Class              |
| ------ | -------------------------- |
| A      | S3 Standard                |
| B      | S3 Standard-IA             |
| C      | Glacier Flexible Retrieval |
| D      | Glacier Deep Archive       |

## Correct Answer

✅ **B. S3 Standard-IA**

## Why Correct?

### Keywords

* Rare access
* Immediate retrieval

Standard-IA is designed for infrequently accessed data that requires instant access.

---

## Why Others Are Wrong?

| Option | Reason                        |
| ------ | ----------------------------- |
| A      | More expensive than necessary |
| C      | Retrieval delay               |
| D      | Long retrieval times          |

---

## Service: Amazon S3 Standard-IA

### Definition

Storage class for infrequently accessed data requiring rapid retrieval.

### Key Features

* Lower storage cost
* Immediate access
* High durability

### Exam Traps

Rarely Used + Immediate Access = Standard-IA

Archive = Glacier

### Memory Trick

IA = Infrequent Access.

### Compare With

| Storage Class | Best For                          |
| ------------- | --------------------------------- |
| Standard      | Frequent Access                   |
| Standard-IA   | Rare Access + Immediate Retrieval |
| Glacier       | Archival Data                     |

---

# Question 608 — AWS Site-to-Site VPN

## Question

A company wants a secure network connection from on premises to AWS within one week.

## Options

| Option | Service              |
| ------ | -------------------- |
| A      | AWS Direct Connect   |
| B      | Amazon VPC           |
| C      | AWS Site-to-Site VPN |
| D      | Edge Location        |

## Correct Answer

✅ **C. AWS Site-to-Site VPN**

## Why Correct?

### Keywords

* Fast setup
* Secure connection
* One week

VPN connections can be established quickly using the public internet.

---

## Why Others Are Wrong?

| Option | Reason                    |
| ------ | ------------------------- |
| A      | Longer provisioning time  |
| B      | Network container only    |
| D      | CloudFront infrastructure |

---

## Service: AWS Site-to-Site VPN

### Definition

Encrypted connection between on-premises networks and AWS over the internet.

### Key Features

* Fast deployment
* Secure tunnel
* Cost-effective connectivity

### Exam Traps

Quick Connection = VPN

Dedicated Connection = Direct Connect

### Memory Trick

VPN = Fast Secure Tunnel.

### Compare With

| Service        | Best For                       |
| -------------- | ------------------------------ |
| VPN            | Quick Setup                    |
| Direct Connect | Dedicated Private Connectivity |

---

# Question 484 — Amazon Neptune

## Question

A company wants to analyze relationships among users, addresses, and transactions to identify fraud.

## Correct Answer

✅ **Amazon Neptune**

## Why Correct?

Fraud detection often relies on relationship mapping.

Graph databases excel at modeling and analyzing relationships.

### Keywords

* Relationship analysis
* Fraud detection
* Connected data

---

## Service: Amazon Neptune

### Definition

Managed graph database service.

### Key Features

* Fraud detection
* Recommendation engines
* Social networks
* Relationship analysis

### Exam Traps

Relationship Analysis = Neptune

Graph Database = Neptune

### Memory Trick

Neptune Connects Everything.

### Compare With

| Service  | Database Type |
| -------- | ------------- |
| Neptune  | Graph         |
| DynamoDB | NoSQL         |
| RDS      | Relational    |

---

# Question 493 — Network ACL

## Question

Which AWS feature acts as a VPC firewall at the subnet level?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | Security Group    |
| B      | Network ACL       |
| C      | Traffic Mirroring |
| D      | Internet Gateway  |

## Correct Answer

✅ **B. Network ACL**

## Why Correct?

Network ACLs operate at the subnet level.

---

## Why Others Are Wrong?

| Option | Reason                  |
| ------ | ----------------------- |
| A      | Instance-level firewall |
| C      | Traffic analysis        |
| D      | Internet connectivity   |

---

## Service: Network ACL

### Definition

Subnet-level virtual firewall.

### Key Features

* Allow rules
* Deny rules
* Stateless processing
* Subnet protection

### Exam Traps

Subnet = NACL

Instance = Security Group

### Memory Trick

NACL = Neighborhood Firewall.

### Compare With

| Feature        | Scope    |
| -------------- | -------- |
| NACL           | Subnet   |
| Security Group | Instance |

---

# Question 604 — Security Group

## Question

Which VPC component acts as a virtual firewall at the EC2 instance level?

## Options

| Option | Service        |
| ------ | -------------- |
| A      | Network ACL    |
| B      | Security Group |
| C      | Route Table    |
| D      | NAT Gateway    |

## Correct Answer

✅ **B. Security Group**

## Why Correct?

Security Groups attach directly to EC2 instances.

---

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | Subnet-level firewall    |
| C      | Routing service          |
| D      | Outbound internet access |

---

## Service: Security Group

### Definition

Instance-level virtual firewall.

### Key Features

* Stateful
* Allow rules only
* EC2 protection

### Exam Traps

Instance = Security Group

Subnet = NACL

### Memory Trick

Security Group Guards the Instance.

### Compare With

| Feature        | Scope    |
| -------------- | -------- |
| Security Group | Instance |
| NACL           | Subnet   |

---

# Batch 10 Cheat Sheet

## 🔥 Top Services

* AWS DMS
* AWS Schema Conversion Tool (SCT)
* AWS Fargate
* Amazon S3 Standard-IA
* AWS Site-to-Site VPN
* Amazon Neptune
* Network ACL
* Security Group

---

## 🔥 Top Facts To Memorize

| Concept                           | Answer         |
| --------------------------------- | -------------- |
| Database Migration                | DMS            |
| Schema Conversion                 | SCT            |
| Containers Without Servers        | Fargate        |
| Rare Access + Immediate Retrieval | S3 Standard-IA |
| Fast Secure Connection            | VPN            |
| Graph Database                    | Neptune        |
| Subnet Firewall                   | NACL           |
| Instance Firewall                 | Security Group |

---

## 🔥 Most Repeated Traps

| Wrong Choice   | Correct Choice                     |
| -------------- | ---------------------------------- |
| Direct Connect | VPN (Quick Setup)                  |
| Security Group | NACL (Subnet Question)             |
| NACL           | Security Group (Instance Question) |
| Glacier        | Standard-IA (Immediate Retrieval)  |
| Lambda         | Fargate (Containers)               |

---

## 🔥 Most Likely To Reappear

1. DMS vs SCT
2. Fargate vs ECS vs EKS
3. VPN vs Direct Connect
4. Security Group vs NACL
5. Standard-IA vs Glacier

---

# Batch 10 Summary

```text
DMS              → Database Migration
SCT              → Schema Conversion
Fargate          → Serverless Containers
Standard-IA      → Rare Access + Instant Retrieval
VPN              → Quick Secure Connectivity
Neptune          → Graph Database
NACL             → Subnet Firewall
Security Group   → Instance Firewall
```
