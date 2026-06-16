# DOMAIN 3 — BATCH 05

## Cloud Technology & Services

---

# Question 75 — AWS Management Console

## Question

A company wants to manage its AWS Cloud resources through a web interface.

## Options

| Option | Service                |
| ------ | ---------------------- |
| A      | AWS Management Console |
| B      | AWS CLI                |
| C      | AWS SDK                |
| D      | AWS Cloud9             |

## Correct Answer

✅ **A. AWS Management Console**

## Why Correct?

### Keywords

* Web interface
* Manage AWS resources

AWS Management Console is the browser-based interface for AWS services.

## Why Others Are Wrong?

| Option | Reason                |
| ------ | --------------------- |
| B      | Command-line tool     |
| C      | Programming libraries |
| D      | Cloud IDE             |

---

## Service: AWS Management Console

### Definition

Web-based interface for managing AWS services.

### Key Features

* Browser access
* Visual management
* No installation required

### Exam Traps

Web Interface = AWS Management Console

### Memory Trick

Console = Dashboard.

### Compare With

| Service | Access Type |
| ------- | ----------- |
| Console | Browser     |
| CLI     | Terminal    |
| SDK     | Code        |

---

# Question 78 — AWS CloudFormation

## Question

A developer needs to maintain development and production infrastructures in a repeatable fashion.

## Options

| Option | Service                 |
| ------ | ----------------------- |
| A      | AWS Ground Station      |
| B      | AWS Shield              |
| C      | AWS IoT Device Defender |
| D      | AWS CloudFormation      |

## Correct Answer

✅ **D. AWS CloudFormation**

## Why Correct?

### Keywords

* Repeatable
* Infrastructure
* Automation

CloudFormation provides Infrastructure as Code (IaC).

## Why Others Are Wrong?

The other services are not infrastructure deployment services.

---

## Service: AWS CloudFormation

### Definition

Infrastructure as Code (IaC) service.

### Key Features

* Templates
* Automation
* Repeatable deployments

### Exam Traps

Repeatable Infrastructure = CloudFormation

### Memory Trick

Formation = Build Infrastructure Automatically.

---

# Question 80 — AWS Global Accelerator

## Question

Which AWS service helps deliver highly available applications with fast failover for Multi-Region and Multi-AZ architectures?

## Options

| Option | Service                |
| ------ | ---------------------- |
| A      | AWS WAF                |
| B      | AWS Global Accelerator |
| C      | AWS Shield             |
| D      | AWS Direct Connect     |

## Correct Answer

✅ **B. AWS Global Accelerator**

## Why Correct?

### Keywords

* Multi-Region
* Fast failover
* High availability

Global Accelerator routes users to optimal endpoints.

## Why Others Are Wrong?

| Option | Reason                         |
| ------ | ------------------------------ |
| A      | Firewall service               |
| C      | DDoS protection                |
| D      | Dedicated network connectivity |

---

## Service: AWS Global Accelerator

### Definition

Improves application availability and performance globally.

### Key Features

* Global routing
* Fast failover
* Static IP addresses

### Exam Traps

CloudFront ≠ Global Accelerator

CloudFront = Content Delivery

Global Accelerator = Application Traffic

### Memory Trick

Accelerator = Fastest Route.

### Compare With

| Service            | Purpose             |
| ------------------ | ------------------- |
| CloudFront         | Content Delivery    |
| Global Accelerator | Application Traffic |

---

# Question 81 — Amazon SQS

## Question

A company has ecommerce applications that need to send messages to each other.

## Options

| Option | Service                |
| ------ | ---------------------- |
| A      | Auto Scaling           |
| B      | Elastic Load Balancing |
| C      | Amazon SQS             |
| D      | Amazon Kinesis         |

## Correct Answer

✅ **C. Amazon SQS**

## Why Correct?

### Keywords

* Applications communicate
* Message exchange

SQS is AWS's queue service.

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| A      | Scaling service        |
| B      | Load balancing service |
| D      | Streaming data service |

---

## Service: Amazon SQS

### Definition

Fully managed message queue service.

### Key Features

* Decouples applications
* Reliable messaging
* Queue-based communication

### Exam Traps

Messaging Between Applications = SQS

Notifications = SNS

### Memory Trick

SQS = Store Messages in Line.

### Compare With

| Service | Purpose |
| ------- | ------- |
| SNS     | Notify  |
| SQS     | Queue   |

---

# Question 85 — Amazon CloudFront

## Question

Which AWS service enables companies to deploy an application close to end users?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | Amazon CloudFront |
| B      | AWS Auto Scaling  |
| C      | AWS AppSync       |
| D      | Amazon Route 53   |

## Correct Answer

✅ **A. Amazon CloudFront**

## Why Correct?

### Keywords

* Close to users
* Low latency

CloudFront uses Edge Locations.

## Why Others Are Wrong?

The remaining services are not CDN services.

---

## Service: Amazon CloudFront

### Definition

AWS Content Delivery Network (CDN).

### Key Features

* Edge locations
* Global caching
* Reduced latency

### Exam Traps

Close to Users = CloudFront

### Memory Trick

CloudFront = Front Door Near Customer.

---

# Question 87 — Amazon S3

## Question

Which AWS service provides highly durable object storage?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | Amazon S3  |
| B      | Amazon EFS |
| C      | Amazon EBS |
| D      | Amazon FSx |

## Correct Answer

✅ **A. Amazon S3**

## Why Correct?

### Keywords

* Object storage
* High durability

Amazon S3 provides 99.999999999% (11 nines) durability.

## Why Others Are Wrong?

| Option | Reason               |
| ------ | -------------------- |
| B      | File storage         |
| C      | Block storage        |
| D      | Managed file systems |

---

## Service: Amazon S3

### Definition

Highly durable object storage service.

### Key Features

* Object storage
* 99.999999999% durability
* Virtually unlimited scale

### Exam Traps

Object Storage = S3

### Memory Trick

S3 = Store Stuff Simply.

### Compare With

| Service | Storage Type |
| ------- | ------------ |
| S3      | Object       |
| EBS     | Block        |
| EFS     | File         |

---

# Question 90 — AWS Storage Gateway

## Question

Which AWS service is a hybrid cloud storage service that provides on-premises users access to virtually unlimited cloud storage?

## Options

| Option | Service             |
| ------ | ------------------- |
| A      | AWS DataSync        |
| B      | Amazon S3 Glacier   |
| C      | AWS Storage Gateway |
| D      | Amazon EBS          |

## Correct Answer

✅ **C. AWS Storage Gateway**

## Why Correct?

### Keywords

* Hybrid
* On-premises
* Cloud storage

Storage Gateway bridges local storage and AWS.

---

## Service: AWS Storage Gateway

### Definition

Hybrid cloud storage integration service.

### Key Features

* File Gateway
* Volume Gateway
* Tape Gateway

### Exam Traps

Hybrid Storage = Storage Gateway

### Memory Trick

Gateway = Bridge.

---

# Question 92 — AWS SDK

## Question

Which tool should a developer use to integrate AWS service features directly into an application?

## Options

| Option | Service                            |
| ------ | ---------------------------------- |
| A      | AWS Software Development Kit (SDK) |
| B      | AWS CodeDeploy                     |
| C      | AWS Lambda                         |
| D      | AWS Batch                          |

## Correct Answer

✅ **A. AWS Software Development Kit (SDK)**

## Why Correct?

### Keywords

* Integrate AWS into application
* Developer

SDK provides APIs and programming libraries.

## Why Others Are Wrong?

The remaining options are not programming libraries.

---

## Service: AWS SDK

### Definition

Programming libraries for AWS integration.

### Key Features

* APIs
* Multiple languages
* Service integration

### Exam Traps

Code Integration = SDK

Command Line = CLI

### Memory Trick

SDK = AWS Tools for Developers.

---

# Question 96 — Amazon Redshift Serverless

## Question

A company wants to operate a data warehouse without managing infrastructure.

## Options

| Option | Service                    |
| ------ | -------------------------- |
| A      | Amazon Aurora              |
| B      | Amazon Redshift Serverless |
| C      | AWS Lambda                 |
| D      | Amazon RDS                 |

## Correct Answer

✅ **B. Amazon Redshift Serverless**

## Why Correct?

### Keywords

* Data warehouse
* Serverless
* Analytics

Redshift Serverless removes infrastructure management.

## Why Others Are Wrong?

The remaining services are not serverless data warehouses.

---

## Service: Amazon Redshift Serverless

### Definition

Serverless cloud data warehouse.

### Key Features

* Analytics
* Data warehousing
* No infrastructure management

### Exam Traps

Analytics Warehouse = Redshift

### Memory Trick

Redshift = Big Data Analytics.

### Compare With

| Service  | Purpose      |
| -------- | ------------ |
| Redshift | Analytics    |
| RDS      | Transactions |
| DynamoDB | NoSQL        |

---

# Batch 05 Cheat Sheet

## 🔥 Top Services

* Amazon S3
* Amazon CloudFront
* AWS Global Accelerator
* Amazon SQS
* AWS CloudFormation
* AWS Storage Gateway
* AWS SDK
* Amazon Redshift Serverless
* AWS Management Console

---

## 🔥 Top Facts To Memorize

| Concept                   | Remember               |
| ------------------------- | ---------------------- |
| Browser Management        | AWS Management Console |
| Repeatable Infrastructure | CloudFormation         |
| Application Failover      | Global Accelerator     |
| Queue Service             | SQS                    |
| CDN                       | CloudFront             |
| Object Storage            | S3                     |
| Hybrid Storage            | Storage Gateway        |
| Code Integration          | SDK                    |
| Data Warehouse            | Redshift               |
| Serverless Data Warehouse | Redshift Serverless    |

---

## 🔥 Common Exam Traps

| Question Says       | Answer                 |
| ------------------- | ---------------------- |
| Browser Interface   | AWS Management Console |
| Queue Messages      | SQS                    |
| Notifications       | SNS                    |
| Object Storage      | S3                     |
| File Storage        | EFS                    |
| Block Storage       | EBS                    |
| Analytics Warehouse | Redshift               |
| CDN                 | CloudFront             |

---

## 🔥 Most Likely To Reappear

1. S3 vs EBS vs EFS
2. SNS vs SQS
3. CloudFront vs Global Accelerator
4. SDK vs CLI
5. Redshift vs RDS vs DynamoDB
