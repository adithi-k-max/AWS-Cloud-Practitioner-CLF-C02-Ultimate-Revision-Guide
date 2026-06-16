# DOMAIN 3 — BATCH 08

## Cloud Technology & Services

---

# Question 497 — Amazon Kinesis

## Question

Which AWS service helps users collect and process streaming data in real time?

## Options

| Option | Service         |
| ------ | --------------- |
| A      | Amazon Athena   |
| B      | Amazon Kinesis  |
| C      | Amazon S3       |
| D      | Amazon Route 53 |

## Correct Answer

✅ **B. Amazon Kinesis**

## Why Correct?

### Keywords

* Real-time
* Streaming
* Continuous data

Kinesis is AWS's streaming data platform.

### Common Use Cases

* IoT data
* Application logs
* Clickstream analytics
* Real-time monitoring

## Why Others Are Wrong?

| Option | Reason                |
| ------ | --------------------- |
| A      | Queries existing data |
| C      | Stores data           |
| D      | DNS service           |

---

## Service: Amazon Kinesis

### Definition

Real-time data streaming service.

### Key Features

* Real-time ingestion
* Analytics pipelines
* Streaming workloads
* Scalable processing

### Exam Traps

Real-Time Stream = Kinesis

### Memory Trick

Kinesis = Continuous Flowing Data.

### Compare With

| Service | Purpose    |
| ------- | ---------- |
| Kinesis | Streaming  |
| Athena  | Query Data |
| S3      | Store Data |

---

# Question 501 — Amazon EBS

## Question

Which AWS service provides scalable block storage volumes for Amazon EC2 instances?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | Amazon S3  |
| B      | Amazon EBS |
| C      | Amazon EFS |
| D      | AWS Backup |

## Correct Answer

✅ **B. Amazon EBS**

## Why Correct?

### Keywords

* EC2
* Block storage

EBS volumes are attached directly to EC2 instances.

## Why Others Are Wrong?

| Option | Reason         |
| ------ | -------------- |
| A      | Object storage |
| C      | File storage   |
| D      | Backup service |

---

## Service: Amazon EBS

### Definition

Persistent block storage for Amazon EC2.

### Key Features

* Block storage
* Persistent volumes
* Snapshot support
* High performance

### Exam Traps

EC2 Disk = EBS

### Memory Trick

EBS = EC2 Hard Drive.

### Compare With

| Service | Storage Type |
| ------- | ------------ |
| EBS     | Block        |
| EFS     | File         |
| S3      | Object       |

---

# Question 504 — Amazon EFS

## Question

A company needs a shared file system that multiple EC2 instances can access simultaneously.

## Options

| Option | Service        |
| ------ | -------------- |
| A      | Amazon S3      |
| B      | Amazon EBS     |
| C      | Amazon EFS     |
| D      | Amazon Glacier |

## Correct Answer

✅ **C. Amazon EFS**

## Why Correct?

### Keywords

* Shared storage
* Multiple EC2 instances

EFS supports concurrent access from multiple EC2 instances.

## Why Others Are Wrong?

| Option | Reason                                 |
| ------ | -------------------------------------- |
| A      | Not a file system                      |
| B      | Typically attached to one EC2 instance |
| D      | Archive storage                        |

---

## Service: Amazon EFS

### Definition

Managed file storage service.

### Key Features

* Shared access
* Multiple EC2 instances
* Automatic scaling
* Fully managed

### Exam Traps

Shared File Storage = EFS

### Memory Trick

EFS = Elastic File System.

### Compare With

| Service | Use Case        |
| ------- | --------------- |
| EBS     | Single EC2 Disk |
| EFS     | Shared Files    |
| S3      | Object Storage  |

---

# Question 507 — Amazon S3 Glacier

## Question

Which AWS service is best suited for long-term archival storage?

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | Amazon S3 Standard |
| B      | Amazon EFS         |
| C      | Amazon S3 Glacier  |
| D      | Amazon EBS         |

## Correct Answer

✅ **C. Amazon S3 Glacier**

## Why Correct?

### Keywords

* Archive
* Long-term
* Low cost

Glacier is optimized for archival storage.

## Why Others Are Wrong?

| Option | Reason                  |
| ------ | ----------------------- |
| A      | Frequent access storage |
| B      | File storage            |
| D      | Block storage           |

---

## Service: Amazon S3 Glacier

### Definition

Low-cost archival storage service.

### Key Features

* Archive data
* Compliance storage
* Long retention
* Extremely low cost

### Exam Traps

Archive = Glacier

### Memory Trick

Cold Data Goes to Glacier.

---

# Question 510 — AWS Lambda

## Question

Which AWS service allows applications to run code without provisioning servers?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | Amazon EC2 |
| B      | AWS Lambda |
| C      | Amazon ECS |
| D      | Amazon EKS |

## Correct Answer

✅ **B. AWS Lambda**

## Why Correct?

### Keywords

* Run code
* No servers
* Event-driven

Lambda is AWS's serverless compute service.

## Why Others Are Wrong?

| Option | Reason                     |
| ------ | -------------------------- |
| A      | Requires server management |
| C      | Container platform         |
| D      | Kubernetes platform        |

---

## Service: AWS Lambda

### Definition

Serverless compute service.

### Key Features

* Event-driven execution
* No server management
* Automatic scaling
* Pay per execution

### Exam Traps

Serverless Code = Lambda

### Memory Trick

Write Code, AWS Runs It.

### Compare With

| Service | Purpose         |
| ------- | --------------- |
| Lambda  | Serverless Code |
| ECS     | Containers      |
| EC2     | Virtual Servers |

---

# Question 514 — Amazon EKS

## Question

Which AWS service provides managed Kubernetes?

## Options

| Option | Service    |
| ------ | ---------- |
| A      | Amazon ECS |
| B      | Amazon EC2 |
| C      | Amazon EKS |
| D      | AWS Batch  |

## Correct Answer

✅ **C. Amazon EKS**

## Why Correct?

### Keywords

* Kubernetes
* Managed

EKS stands for Elastic Kubernetes Service.

## Why Others Are Wrong?

| Option | Reason                            |
| ------ | --------------------------------- |
| A      | Container service, not Kubernetes |
| B      | Virtual machines                  |
| D      | Batch processing                  |

---

## Service: Amazon EKS

### Definition

Managed Kubernetes service.

### Key Features

* Kubernetes
* Managed control plane
* Container orchestration
* High availability

### Exam Traps

Kubernetes = EKS

Containers = ECS

### Memory Trick

K = Kubernetes = EKS.

---

# Question 518 — AWS Auto Scaling

## Question

Which AWS service automatically adjusts the number of EC2 instances to match demand?

## Options

| Option | Service                |
| ------ | ---------------------- |
| A      | Elastic Load Balancing |
| B      | Amazon Route 53        |
| C      | AWS Auto Scaling       |
| D      | AWS Organizations      |

## Correct Answer

✅ **C. AWS Auto Scaling**

## Why Correct?

### Keywords

* Automatically adjust
* EC2 count
* Demand changes

Auto Scaling increases or decreases resources based on demand.

## Why Others Are Wrong?

| Option | Reason              |
| ------ | ------------------- |
| A      | Distributes traffic |
| B      | DNS service         |
| D      | Account management  |

---

## Service: AWS Auto Scaling

### Definition

Automatically adjusts AWS resources based on demand.

### Key Features

* High availability
* Cost optimization
* Automatic scaling
* Dynamic resource management

### Exam Traps

Increase EC2 Count = Auto Scaling

### Memory Trick

Traffic Up? Auto Scaling Up.

---

# Question 521 — Elastic Load Balancing (ELB)

## Question

Which AWS service distributes incoming application traffic across multiple targets?

## Options

| Option | Service                |
| ------ | ---------------------- |
| A      | Elastic Load Balancing |
| B      | AWS Auto Scaling       |
| C      | Amazon Route 53        |
| D      | AWS CloudFormation     |

## Correct Answer

✅ **A. Elastic Load Balancing (ELB)**

## Why Correct?

### Keywords

* Distribute traffic
* Multiple servers

ELB balances incoming requests across targets.

## Why Others Are Wrong?

| Option | Reason                       |
| ------ | ---------------------------- |
| B      | Creates or removes instances |
| C      | DNS service                  |
| D      | Infrastructure deployment    |

---

## Service: Elastic Load Balancing (ELB)

### Definition

Distributes incoming traffic across multiple targets.

### Key Features

* High availability
* Fault tolerance
* Traffic distribution
* Improved reliability

### Exam Traps

Traffic Distribution = ELB

Instance Count = Auto Scaling

### Memory Trick

Load Balancer = Traffic Manager.

### Compare With

| Service      | Purpose            |
| ------------ | ------------------ |
| ELB          | Distribute Traffic |
| Auto Scaling | Scale Instances    |

---

# Batch 08 Cheat Sheet

## 🔥 Top Services

* Amazon Kinesis
* Amazon EBS
* Amazon EFS
* Amazon S3 Glacier
* AWS Lambda
* Amazon EKS
* AWS Auto Scaling
* Elastic Load Balancing (ELB)

---

## 🔥 Top Facts To Memorize

| Concept               | Remember     |
| --------------------- | ------------ |
| Streaming Data        | Kinesis      |
| EC2 Disk              | EBS          |
| Shared File System    | EFS          |
| Archival Storage      | Glacier      |
| Serverless Code       | Lambda       |
| Kubernetes            | EKS          |
| Automatic EC2 Scaling | Auto Scaling |
| Traffic Distribution  | ELB          |

---

## 🔥 Common Exam Traps

| Question Says      | Answer       |
| ------------------ | ------------ |
| Serverless Code    | Lambda       |
| Kubernetes         | EKS          |
| Containers         | ECS          |
| EC2 Storage        | EBS          |
| Shared Files       | EFS          |
| Archive Data       | Glacier      |
| Scale Instances    | Auto Scaling |
| Distribute Traffic | ELB          |

---

## 🔥 Most Likely To Reappear

1. Lambda vs EC2
2. ECS vs EKS
3. EBS vs EFS vs S3
4. Auto Scaling vs ELB
5. Glacier vs S3 Standard
