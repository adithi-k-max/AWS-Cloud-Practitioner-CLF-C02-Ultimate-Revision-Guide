# DOMAIN 3 — BATCH 07

## Cloud Technology & Services

---

# Question 613 — AWS DataSync

## Question

A company plans to perform a one-time migration of a large dataset with millions of files from its on-premises data center to the AWS Cloud.

Which AWS service should the company use for the migration?

## Options

| Option | Service                                  |
| ------ | ---------------------------------------- |
| A      | AWS Database Migration Service (AWS DMS) |
| B      | AWS DataSync                             |
| C      | AWS Migration Hub                        |
| D      | AWS Application Migration Service        |

## Correct Answer

✅ **B. AWS DataSync**

## Why Correct?

### Keywords

* Millions of files
* Large dataset
* Data migration

DataSync is built specifically for transferring large amounts of file data into AWS.

## Why Others Are Wrong?

| Option | Reason                                               |
| ------ | ---------------------------------------------------- |
| A      | Migrates databases, not file datasets                |
| C      | Tracks migrations but does not transfer files        |
| D      | Migrates servers and applications, not file datasets |

---

## Service: AWS DataSync

### Definition

Online data transfer service between on-premises systems and AWS storage.

### Key Features

* Automated transfer
* High-speed migration
* Supports S3
* Supports EFS
* Supports FSx

### Exam Traps

File Migration = DataSync

Database Migration = DMS

### Memory Trick

DataSync = Sync Data Quickly.

### Compare With

| Service       | Purpose            |
| ------------- | ------------------ |
| DataSync      | File Migration     |
| DMS           | Database Migration |
| Migration Hub | Migration Tracking |

---

# Question 615 — Amazon Polly

## Question

A company wants to develop an accessibility application that will convert text into audible speech.

Which AWS service will meet this requirement?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | Amazon MQ         |
| B      | Amazon Polly      |
| C      | Amazon Neptune    |
| D      | Amazon Timestream |

## Correct Answer

✅ **B. Amazon Polly**

## Why Correct?

Polly converts text into natural-sounding speech.

## Why Others Are Wrong?

| Option | Reason               |
| ------ | -------------------- |
| A      | Message broker       |
| C      | Graph database       |
| D      | Time-series database |

---

## Service: Amazon Polly

### Definition

Text-to-speech service.

### Key Features

* Natural voices
* Multiple languages
* Accessibility applications
* Neural voices

### Exam Traps

Text → Speech = Polly

### Memory Trick

Polly Talks.

### Compare With

| Service    | Purpose                |
| ---------- | ---------------------- |
| Polly      | Text → Speech          |
| Transcribe | Speech → Text          |
| Lex        | Conversational Chatbot |

---

# Question 616 — AWS Direct Connect

## Question

A company needs dedicated network connectivity between its on-premises data center and AWS. The network cannot use the public internet.

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | AWS Transit Gateway |
| B      | AWS VPN             |
| C      | Amazon CloudFront   |
| D      | AWS Direct Connect  |

## Correct Answer

✅ **D. AWS Direct Connect**

## Why Correct?

### Keywords

* Dedicated connection
* No public internet
* Private connectivity

Direct Connect provides private connectivity directly into AWS.

## Why Others Are Wrong?

| Option | Reason                               |
| ------ | ------------------------------------ |
| A      | Network hub, not a dedicated circuit |
| B      | Uses public internet                 |
| C      | Content Delivery Network             |

---

## Service: AWS Direct Connect

### Definition

Dedicated private network connection between on-premises infrastructure and AWS.

### Key Features

* Private connectivity
* Consistent performance
* Reduced latency
* Predictable bandwidth

### Exam Traps

Private Dedicated Connection = Direct Connect

VPN = Internet-Based Connection

### Memory Trick

Direct Connect = Private Highway to AWS.

---

# Question 617 — Amazon QuickSight

## Question

A company needs dashboards and charts to analyze business data.

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | Amazon Macie      |
| B      | Amazon Aurora     |
| C      | Amazon QuickSight |
| D      | AWS CloudTrail    |

## Correct Answer

✅ **C. Amazon QuickSight**

## Why Correct?

QuickSight is AWS's business intelligence and visualization platform.

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | Sensitive data discovery |
| B      | Database service         |
| D      | Audit logging service    |

---

## Service: Amazon QuickSight

### Definition

Business intelligence and analytics service.

### Key Features

* Dashboards
* Reports
* Visualizations
* Interactive analytics

### Exam Traps

Charts + Dashboards = QuickSight

### Memory Trick

QuickSight Helps You "See" Business Data.

### Compare With

| Service    | Purpose        |
| ---------- | -------------- |
| QuickSight | Visualization  |
| Glue       | ETL            |
| Redshift   | Data Warehouse |

---

# Question 492 — Amazon ECS

## Question

Which AWS compute service gives users the ability to securely and reliably run containers at scale?

## Options

| Option | Service                                       |
| ------ | --------------------------------------------- |
| A      | Amazon Elastic Container Service (Amazon ECS) |
| B      | Amazon Aurora                                 |
| C      | Amazon Athena                                 |
| D      | Amazon Polly                                  |

## Correct Answer

✅ **A. Amazon ECS**

## Why Correct?

### Keywords

* Containers
* Scale
* Managed service

ECS is AWS's container orchestration platform.

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| B      | Database service       |
| C      | Query service          |
| D      | Text-to-speech service |

---

## Service: Amazon ECS

### Definition

Managed container orchestration service.

### Key Features

* Docker containers
* Scaling
* High availability
* Integration with Fargate

### Exam Traps

Containers = ECS

Serverless Containers = Fargate

### Compare With

| Service | Purpose                      |
| ------- | ---------------------------- |
| ECS     | Container Platform           |
| Fargate | Serverless Container Compute |

---

# Question 495 — Amazon SNS

## Question

Which AWS service can be used to send alerts when a specific Amazon CloudWatch alarm is invoked?

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | AWS CloudTrail     |
| B      | Amazon SNS         |
| C      | Amazon SQS         |
| D      | Amazon EventBridge |

## Correct Answer

✅ **B. Amazon SNS**

## Why Correct?

SNS is used for notifications and alerts.

## Why Others Are Wrong?

| Option | Reason                |
| ------ | --------------------- |
| A      | Audit logs            |
| C      | Queue service         |
| D      | Event routing service |

---

## Service: Amazon SNS

### Definition

Notification service.

### Key Features

* Email alerts
* SMS alerts
* Push notifications
* Fan-out messaging

### Exam Traps

Alert Users = SNS

Queue Messages = SQS

### Memory Trick

SNS = Notify Everyone.

### Compare With

| Service | Purpose       |
| ------- | ------------- |
| SNS     | Notifications |
| SQS     | Queues        |

---

# Question 496 — Amazon Route 53

## Question

A cloud practitioner wants a highly available and scalable DNS service.

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | Amazon Route 53     |
| B      | Amazon Lightsail    |
| C      | AWS Amplify Hosting |
| D      | Amazon S3           |

## Correct Answer

✅ **A. Amazon Route 53**

## Why Correct?

Route 53 is AWS's managed DNS service.

## Why Others Are Wrong?

| Option | Reason                      |
| ------ | --------------------------- |
| B      | Hosting service             |
| C      | Frontend deployment service |
| D      | Storage service             |

---

## Service: Amazon Route 53

### Definition

Highly available DNS service.

### Key Features

* Domain registration
* DNS routing
* Health checks
* Traffic routing policies

### Exam Traps

DNS = Route 53

### Memory Trick

Route Traffic → Route 53.

### Compare With

| Service    | Purpose          |
| ---------- | ---------------- |
| Route 53   | DNS              |
| CloudFront | Content Delivery |

---

# Batch 07 Cheat Sheet

## 🔥 Top Services

* AWS DataSync
* Amazon Polly
* AWS Direct Connect
* Amazon QuickSight
* Amazon ECS
* Amazon SNS
* Amazon Route 53

---

## 🔥 Top Facts To Memorize

| Concept            | Remember       |
| ------------------ | -------------- |
| File Migration     | DataSync       |
| Text-to-Speech     | Polly          |
| Private Connection | Direct Connect |
| Dashboards         | QuickSight     |
| Containers         | ECS            |
| Notifications      | SNS            |
| DNS                | Route 53       |

---

## 🔥 Common Exam Traps

| Question Says      | Answer     |
| ------------------ | ---------- |
| File Transfer      | DataSync   |
| Database Migration | DMS        |
| Text → Speech      | Polly      |
| Speech → Text      | Transcribe |
| DNS                | Route 53   |
| Notification       | SNS        |
| Queue              | SQS        |
| Containers         | ECS        |

---

## 🔥 Most Likely To Reappear

1. DataSync vs DMS
2. Polly vs Transcribe
3. Direct Connect vs VPN
4. SNS vs SQS
5. Route 53 vs CloudFront
