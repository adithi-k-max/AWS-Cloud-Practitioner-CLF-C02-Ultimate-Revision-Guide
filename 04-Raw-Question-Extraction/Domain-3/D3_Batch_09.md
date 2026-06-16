# DOMAIN 3 — BATCH 09

## Cloud Technology & Services

---

# Question 591 — AWS CloudFormation

## Question

Which AWS service enables users to create copies of resources across AWS Regions?

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | Amazon ElastiCache  |
| B      | AWS CloudFormation  |
| C      | AWS CloudTrail      |
| D      | AWS Systems Manager |

## Correct Answer

✅ **B. AWS CloudFormation**

## Why Correct?

CloudFormation StackSets can deploy infrastructure across multiple AWS Regions and accounts.

### Keywords

* Multiple Regions
* Infrastructure copies
* Repeatable deployment

## Why Others Are Wrong?

| Option | Reason                        |
| ------ | ----------------------------- |
| A      | Caching service only          |
| C      | Auditing service              |
| D      | Operations management service |

---

## Service: AWS CloudFormation

### Definition

Infrastructure as Code (IaC) service.

### Key Features

* Templates
* Automation
* Multi-Region deployment
* StackSets

### Exam Traps

Infrastructure Replication ≠ CloudTrail

Infrastructure Deployment = CloudFormation

### Memory Trick

CloudFormation = Build Infrastructure from Templates.

---

# Question 593 — Amazon EBS Snapshot

## Question

A user needs to perform a one-time backup of an Amazon EBS volume attached to an EC2 instance.

What is the MOST operationally efficient way?

## Options

| Option | Action                                      |
| ------ | ------------------------------------------- |
| A      | Attach another EBS volume and copy contents |
| B      | Copy outside AWS through Direct Connect     |
| C      | Create an EBS Snapshot                      |
| D      | Write custom script to S3                   |

## Correct Answer

✅ **C. Create an EBS Snapshot**

## Why Correct?

Snapshots are AWS-native backups for EBS volumes.

They are simple, automated, and operationally efficient.

## Why Others Are Wrong?

| Option | Reason                                      |
| ------ | ------------------------------------------- |
| A      | Manual process                              |
| B      | Unnecessary complexity                      |
| D      | Requires custom development and maintenance |

---

## Service: Amazon EBS Snapshot

### Definition

Point-in-time backup of an EBS volume.

### Key Features

* Incremental backups
* Disaster recovery
* Restore capability
* Snapshot storage in Amazon S3

### Exam Traps

Backup EBS Volume = Snapshot

### Memory Trick

Snapshot = Save Game.

### Compare With

| Service      | Purpose                       |
| ------------ | ----------------------------- |
| EBS Snapshot | Backup                        |
| EBS Volume   | Storage                       |
| AWS Backup   | Centralized Backup Management |

---

# Question 594 — Amazon Lightsail

## Question

A developer with no AWS experience wants to build a web application quickly.

## Options

| Option | Service          |
| ------ | ---------------- |
| A      | Amazon SageMaker |
| B      | AWS Lambda       |
| C      | Amazon Lightsail |
| D      | Amazon ECS       |

## Correct Answer

✅ **C. Amazon Lightsail**

## Why Correct?

Lightsail is designed for beginners and simplifies cloud deployment.

It bundles:

* Compute
* Storage
* Networking

into one easy-to-manage service.

## Why Others Are Wrong?

| Option | Reason                                     |
| ------ | ------------------------------------------ |
| A      | Machine Learning platform                  |
| B      | Requires serverless architecture knowledge |
| D      | Container orchestration platform           |

---

## Service: Amazon Lightsail

### Definition

Simplified cloud platform for developers and small workloads.

### Key Features

* Easy deployment
* Fixed pricing
* VPS hosting
* Simplified management

### Exam Traps

Beginner Developer = Lightsail

### Memory Trick

Lightsail = Easy AWS Starter Pack.

### Compare With

| Service   | Best For     |
| --------- | ------------ |
| Lightsail | Beginners    |
| EC2       | Full Control |
| ECS       | Containers   |

---

# Question 484 — Amazon Neptune

## Question

A company wants to run graph queries to detect relationships that might indicate fraud.

Which AWS database service should be used?

## Correct Answer

✅ **Amazon Neptune**

## Why Correct?

### Keywords

* Graph database
* Relationships
* Fraud detection

Neptune is AWS's managed graph database service.

It excels at analyzing relationships between data points.

### Common Use Cases

* Fraud detection
* Social networks
* Recommendation engines
* Knowledge graphs

## Why Others Are Wrong?

RDS, DynamoDB, and Aurora are not graph databases.

---

## Service: Amazon Neptune

### Definition

Managed graph database service.

### Key Features

* Relationship analysis
* Fraud detection
* Social networking
* Knowledge graphs

### Exam Traps

Graph Database = Neptune

### Memory Trick

Neptune Connects Everything Like an Underwater Network.

### Compare With

| Service  | Database Type |
| -------- | ------------- |
| Neptune  | Graph         |
| DynamoDB | NoSQL         |
| RDS      | Relational    |
| Aurora   | Relational    |

---

# Question 494 — Amazon EC2 Spot Instances

## Question

A batch application is fault tolerant and can handle interruptions.

Which EC2 pricing option minimizes cost?

## Options

| Option | Service                        |
| ------ | ------------------------------ |
| A      | Amazon Macie                   |
| B      | Amazon Neptune                 |
| C      | Amazon EC2 Spot Instances      |
| D      | Amazon EC2 On-Demand Instances |

## Correct Answer

✅ **C. Amazon EC2 Spot Instances**

## Why Correct?

### Keywords

* Fault tolerant
* Can be interrupted
* Lowest cost

Spot Instances use spare AWS capacity and provide the largest discounts.

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | Security service         |
| B      | Database service         |
| D      | More expensive than Spot |

---

## Service: Amazon EC2 Spot Instances

### Definition

Unused AWS capacity offered at significant discounts.

### Key Features

* Up to 90% cheaper
* Interruptible
* Ideal for batch processing
* Cost optimization

### Exam Traps

Can Tolerate Interruption = Spot Instances

Must Stay Running = Reserved or On-Demand

### Memory Trick

Spot = Spare Capacity.

### Compare With

| Pricing Model | Best For                |
| ------------- | ----------------------- |
| Spot          | Interruptible Workloads |
| Reserved      | Predictable Workloads   |
| On-Demand     | Unpredictable Workloads |

---

# Batch 09 Cheat Sheet

## 🔥 Top Services

* AWS CloudFormation
* Amazon EBS Snapshots
* Amazon Lightsail
* Amazon Neptune
* Amazon EC2 Spot Instances

---

## 🔥 Must Memorize

| Concept                     | Answer         |
| --------------------------- | -------------- |
| Graph Database              | Neptune        |
| Backup EBS                  | Snapshot       |
| Beginner Hosting            | Lightsail      |
| Interruptible Workload      | Spot Instances |
| Multi-Region Infrastructure | CloudFormation |

---

## 🔥 Repeated Exam Traps

| Keyword                     | Answer         |
| --------------------------- | -------------- |
| Graph Database              | Neptune        |
| EBS Backup                  | Snapshot       |
| Beginner AWS Service        | Lightsail      |
| Cheap Interruptible Compute | Spot Instances |
| Infrastructure as Code      | CloudFormation |

---

## 🔥 Most Likely To Reappear

1. Neptune vs DynamoDB vs RDS
2. Spot vs Reserved vs On-Demand
3. CloudFormation vs CloudTrail
4. Lightsail vs EC2
5. Snapshot vs Backup Services

---

# Batch 09 Summary

```text
CloudFormation → Infrastructure as Code
EBS Snapshot   → Backup EBS Volumes
Lightsail      → Beginner-Friendly Hosting
Neptune        → Graph Database
Spot Instances → Cheapest Interruptible Compute
```
