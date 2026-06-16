# DOMAIN 3 — BATCH 04

## Cloud Technology & Services

---

# Question 51 — AWS Cloud Development Kit (AWS CDK)

## Question

Which of the following is a software development framework that a company can use to define cloud resources as code and provision the resources through AWS CloudFormation?

## Options

| Option | Service                             |
| ------ | ----------------------------------- |
| A      | AWS CLI                             |
| B      | AWS Developer Center                |
| C      | AWS Cloud Development Kit (AWS CDK) |
| D      | AWS CodeStar                        |

## Correct Answer

✅ **C. AWS Cloud Development Kit (AWS CDK)**

## Why Correct?

### Keywords

* Define cloud resources as code
* CloudFormation
* Framework

AWS CDK allows developers to use programming languages to create CloudFormation infrastructure.

## Why Others Are Wrong?

| Option | Reason                      |
| ------ | --------------------------- |
| A      | Command-line tool only      |
| B      | Learning resource           |
| D      | Development project service |

---

## Service: AWS CDK

### Definition

Framework for defining cloud infrastructure using code.

### Key Features

* Python
* Java
* TypeScript
* Generates CloudFormation templates

### Exam Traps

CDK ≠ CloudFormation

CDK creates CloudFormation.

### Memory Trick

CDK = Coding Cloud Infrastructure.

### Compare With

| Service        | Purpose               |
| -------------- | --------------------- |
| AWS CDK        | Code Infrastructure   |
| CloudFormation | Deploy Infrastructure |

---

# Question 55 — Amazon DynamoDB

## Question

To reduce costs, a company is planning to migrate a NoSQL database to AWS.

Which AWS service is fully managed and can automatically scale throughput capacity?

## Options

| Option | Service         |
| ------ | --------------- |
| A      | Amazon Redshift |
| B      | Amazon Aurora   |
| C      | Amazon DynamoDB |
| D      | Amazon RDS      |

## Correct Answer

✅ **C. Amazon DynamoDB**

## Why Correct?

### Keywords

* NoSQL
* Fully managed
* Auto scaling

DynamoDB is AWS's serverless NoSQL database.

## Why Others Are Wrong?

| Option | Reason                      |
| ------ | --------------------------- |
| A      | Data warehouse              |
| B      | Relational database         |
| D      | Relational database service |

---

## Service: Amazon DynamoDB

### Definition

Fully managed NoSQL database.

### Key Features

* Key-value storage
* Serverless
* Auto scaling
* Single-digit millisecond latency

### Exam Traps

NoSQL = DynamoDB

### Memory Trick

Dynamo = Dynamic NoSQL.

### Compare With

| Service  | Type  |
| -------- | ----- |
| DynamoDB | NoSQL |
| RDS      | SQL   |
| Aurora   | SQL   |

---

# Question 61 — Amazon Aurora

## Question

Which of the following is a fully managed MySQL-compatible database?

## Options

| Option | Service         |
| ------ | --------------- |
| A      | Amazon S3       |
| B      | Amazon DynamoDB |
| C      | Amazon Redshift |
| D      | Amazon Aurora   |

## Correct Answer

✅ **D. Amazon Aurora**

## Why Correct?

Aurora is compatible with:

* MySQL
* PostgreSQL

while providing higher performance.

## Why Others Are Wrong?

| Option | Reason          |
| ------ | --------------- |
| A      | Storage service |
| B      | NoSQL database  |
| C      | Data warehouse  |

---

## Service: Amazon Aurora

### Definition

High-performance managed relational database.

### Key Features

* MySQL compatible
* PostgreSQL compatible
* Managed backups
* High availability

### Exam Traps

MySQL-Compatible = Aurora

### Memory Trick

Aurora = Faster RDS.

### Compare With

| Service  | Purpose             |
| -------- | ------------------- |
| Aurora   | Relational Database |
| DynamoDB | NoSQL               |
| Redshift | Analytics           |

---

# Question 62 — AWS Outposts

## Question

Which AWS service supports a hybrid architecture that extends AWS infrastructure and services to on-premises facilities?

## Options

| Option | Service         |
| ------ | --------------- |
| A      | AWS Snowmobile  |
| B      | AWS Local Zones |
| C      | AWS Outposts    |
| D      | AWS Fargate     |

## Correct Answer

✅ **C. AWS Outposts**

## Why Correct?

### Keywords

* Hybrid architecture
* On-premises
* AWS infrastructure

Outposts brings AWS hardware into customer facilities.

## Why Others Are Wrong?

| Option | Reason                         |
| ------ | ------------------------------ |
| A      | Data transfer service          |
| B      | Infrastructure closer to users |
| D      | Container service              |

---

## Service: AWS Outposts

### Definition

AWS infrastructure installed in customer data centers.

### Key Features

* Hybrid cloud
* Local AWS services
* On-premises deployment

### Exam Traps

Hybrid Infrastructure = Outposts

### Memory Trick

Outpost = AWS Outside AWS.

### Compare With

| Service     | Purpose         |
| ----------- | --------------- |
| Outposts    | AWS On-Premises |
| Local Zones | AWS Near Users  |
| Regions     | Main AWS Sites  |

---

# Question 63 — Amazon RDS

## Question

Which AWS service can run a managed PostgreSQL database that provides OLTP?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | DynamoDB   |
| B      | Athena     |
| C      | Amazon RDS |
| D      | Amazon EMR |

## Correct Answer

✅ **C. Amazon RDS**

## Why Correct?

### Keywords

* PostgreSQL
* Managed database
* OLTP

RDS supports PostgreSQL directly.

## Why Others Are Wrong?

| Option | Reason              |
| ------ | ------------------- |
| A      | NoSQL database      |
| B      | Query service       |
| D      | Big data processing |

---

## Service: Amazon RDS

### Definition

Managed relational database service.

### Key Features

* MySQL
* PostgreSQL
* MariaDB
* Oracle
* SQL Server

### Exam Traps

Relational Database = RDS

### Memory Trick

RDS = Relational Database Service.

### Compare With

| Service  | Type       |
| -------- | ---------- |
| RDS      | Relational |
| DynamoDB | NoSQL      |

---

# Question 64 — Amazon WorkSpaces & Amazon AppStream 2.0

## Question

A company wants managed Windows virtual desktops and applications for remote employees.

Which services should be used? (Choose two.)

## Options

| Option | Service              |
| ------ | -------------------- |
| A      | Amazon Connect       |
| B      | Amazon AppStream 2.0 |
| C      | Amazon WorkSpaces    |
| D      | Site-to-Site VPN     |
| E      | Amazon ECS           |

## Correct Answers

✅ **B. Amazon AppStream 2.0**

✅ **C. Amazon WorkSpaces**

## Why Correct?

* WorkSpaces = Virtual Desktop
* AppStream 2.0 = Application Streaming

## Why Others Are Wrong?

The remaining services do not provide managed virtual desktop environments.

---

## Service: Amazon WorkSpaces

### Definition

Managed virtual desktop service.

### Key Features

* Cloud desktop
* Windows support
* Linux support

### Memory Trick

WorkSpace = Desktop.

---

## Service: Amazon AppStream 2.0

### Definition

Application streaming service.

### Key Features

* Stream applications
* No local installation required

### Memory Trick

AppStream = Stream Apps.

---

# Question 66 — Amazon DynamoDB

## Question

Which AWS service is a key-value database that provides sub-millisecond latency at scale?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | Amazon DynamoDB   |
| B      | Amazon Aurora     |
| C      | Amazon DocumentDB |
| D      | Amazon Neptune    |

## Correct Answer

✅ **A. Amazon DynamoDB**

## Why Correct?

### Keywords

* Key-value database
* Massive scale
* Low latency

Classic DynamoDB question.

### Exam Trap

Key-Value Database = DynamoDB

### Memory Trick

DynamoDB = Massive Scale + Millisecond Performance.

---

# Question 68 — AMIs & EBS Snapshots

## Question

Which AWS services provide disaster recovery solutions for EC2? (Choose two.)

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | Reserved Instances |
| B      | AMIs               |
| C      | EBS Snapshots      |
| D      | AWS Shield         |
| E      | Amazon GuardDuty   |

## Correct Answers

✅ **B. AMIs**

✅ **C. EBS Snapshots**

## Why Correct?

AMIs and Snapshots allow restoration of EC2 environments.

## Why Others Are Wrong?

The remaining services are not backup or disaster recovery solutions.

---

## Service: AMIs & EBS Snapshots

### Definition

Backup and recovery mechanisms for EC2 instances.

### Key Features

* Restore servers
* Disaster recovery
* Backup storage

### Exam Traps

Disaster Recovery = AMI + Snapshot

### Memory Trick

Snapshot = Save Game.

---

# Question 69 — AWS CloudShell

## Question

Which AWS service provides command-line access to AWS tools directly from a browser?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | CloudHSM          |
| B      | AWS CloudShell    |
| C      | Amazon WorkSpaces |
| D      | AWS Cloud Map     |

## Correct Answer

✅ **B. AWS CloudShell**

## Why Correct?

CloudShell provides browser-based terminal access.

---

## Service: AWS CloudShell

### Definition

Browser-based AWS terminal.

### Key Features

* CLI access
* No installation required

### Memory Trick

Shell in the Cloud.

---

# Question 70 — AWS Transit Gateway

## Question

A company expects hundreds of VPCs connected through Direct Connect over time.

Which service simplifies and scales connectivity?

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | VPC Endpoints       |
| B      | AWS Transit Gateway |
| C      | Route 53            |
| D      | Secrets Manager     |

## Correct Answer

✅ **B. AWS Transit Gateway**

## Why Correct?

### Keywords

* Many VPCs
* Scalability
* Networking hub

Transit Gateway acts as a central router.

## Why Others Are Wrong?

The remaining services are not designed for large-scale VPC interconnection.

---

## Service: AWS Transit Gateway

### Definition

Central networking hub for connecting VPCs and on-premises networks.

### Key Features

* Hub-and-spoke model
* Scalable networking

### Memory Trick

Transit Station for Networks.

### Compare With

| Service         | Purpose   |
| --------------- | --------- |
| Transit Gateway | Many VPCs |
| VPC Peering     | Two VPCs  |

---

# Batch 04 Cheat Sheet

## 🔥 Top Services

* Amazon DynamoDB
* Amazon Aurora
* Amazon RDS
* AWS Outposts
* AWS Transit Gateway
* AWS CloudShell
* Amazon WorkSpaces
* Amazon AppStream 2.0
* AWS CDK
* AMIs & EBS Snapshots

---

## 🔥 Top Facts To Memorize

| Concept                          | Remember        |
| -------------------------------- | --------------- |
| NoSQL                            | DynamoDB        |
| MySQL-Compatible                 | Aurora          |
| PostgreSQL Managed Database      | RDS             |
| Hybrid AWS Infrastructure        | Outposts        |
| Many VPCs                        | Transit Gateway |
| Browser Terminal                 | CloudShell      |
| Virtual Desktop                  | WorkSpaces      |
| Application Streaming            | AppStream 2.0   |
| Infrastructure as Code Framework | AWS CDK         |
| Disaster Recovery                | AMI + Snapshot  |

---

## 🔥 Most Likely To Reappear

1. DynamoDB vs RDS
2. Aurora vs RDS
3. Outposts vs Local Zones
4. Transit Gateway vs VPC Peering
5. WorkSpaces vs AppStream 2.0
