# DOMAIN 3 — BATCH 03

## Cloud Technology & Services

---

# Question 20 — Reserved Instances

## Question

An online gaming company needs to choose a purchasing option to run its Amazon EC2 instances for 1 year. The web traffic is consistent, and any increases in traffic are predictable. The EC2 instances must be online and available without disruption.

## Options

| Option | Purchasing Option   |
| ------ | ------------------- |
| A      | On-Demand Instances |
| B      | Reserved Instances  |
| C      | Spot Instances      |
| D      | Spot Fleet          |

## Correct Answer

✅ **B. Reserved Instances**

## Why Correct?

### Keywords

* 1 year
* Predictable workload
* Always available
* Cost effective

Reserved Instances are designed exactly for predictable workloads.

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | More expensive           |
| C      | Can be interrupted       |
| D      | Still uses Spot capacity |

---

## Service: Reserved Instances

### Definition

Long-term commitment pricing model.

### Key Features

* 1 or 3 year commitment
* Significant discount
* Predictable workloads

### Exam Traps

Predictable workload = Reserved Instances

### Memory Trick

Reserve = Book in advance for discount.

### Compare With

| Service   | Best For      |
| --------- | ------------- |
| Reserved  | Predictable   |
| Spot      | Interruptible |
| On-Demand | Unpredictable |

---

# Question 21 — AWS Direct Connect

## Question

Which AWS service or feature allows a user to establish a dedicated network connection between an on-premises data center and AWS?

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | AWS Direct Connect |
| B      | VPC Peering        |
| C      | AWS VPN            |
| D      | Route 53           |

## Correct Answer

✅ **A. AWS Direct Connect**

## Why Correct?

### Keywords

* Dedicated connection
* On-premises
* AWS

Direct Connect provides private dedicated connectivity.

## Why Others Are Wrong?

| Option | Reason               |
| ------ | -------------------- |
| B      | Connects VPCs        |
| C      | Uses public internet |
| D      | DNS service          |

---

## Service: AWS Direct Connect

### Definition

Dedicated private network connection between on-premises and AWS.

### Key Features

* Low latency
* Private connectivity
* Consistent throughput

### Exam Traps

Dedicated Connection = Direct Connect

VPN = Public Internet

### Memory Trick

Direct Connect = Private Highway.

### Compare With

| Service        | Connectivity    |
| -------------- | --------------- |
| Direct Connect | Private         |
| VPN            | Public Internet |

---

# Question 22 — AWS Region

## Question

Which option is a physical location of the AWS global infrastructure?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | AWS DataSync      |
| B      | AWS Region        |
| C      | Amazon Connect    |
| D      | AWS Organizations |

## Correct Answer

✅ **B. AWS Region**

## Why Correct?

Region = Physical geographic location containing multiple Availability Zones.

## Why Others Are Wrong?

| Option | Reason                     |
| ------ | -------------------------- |
| A      | Data transfer service      |
| C      | Contact center service     |
| D      | Account management service |

---

## Service: AWS Region

### Definition

Geographical area containing AWS infrastructure.

### Key Features

* Multiple Availability Zones
* Fault tolerance
* Geographic deployment

### Exam Traps

Region ≠ Availability Zone

### Memory Trick

Region = Country

AZ = City

---

# Question 24 — Internet Gateway

## Question

What is the purpose of having an internet gateway within a VPC?

## Options

| Option | Description                                  |
| ------ | -------------------------------------------- |
| A      | Create VPN connection                        |
| B      | Allow communication between VPC and internet |
| C      | Impose bandwidth constraints                 |
| D      | Load balance internet traffic                |

## Correct Answer

✅ **B. Allow communication between the VPC and the internet**

## Why Correct?

Internet Gateway is required for public internet access.

## Why Others Are Wrong?

| Option | Reason                      |
| ------ | --------------------------- |
| A      | VPN Gateway handles VPN     |
| C      | Not its purpose             |
| D      | ELB performs load balancing |

---

## Service: Internet Gateway

### Definition

Enables communication between a VPC and the internet.

### Key Features

* Public internet access
* Required for public subnets

### Exam Traps

Internet Access = Internet Gateway

### Memory Trick

Gateway = Door to the Internet.

---

# Question 31 — Amazon SNS

## Question

Which AWS service or feature is used to send both text and email messages from distributed applications?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | Amazon SNS        |
| B      | Amazon SES        |
| C      | CloudWatch Alerts |
| D      | Amazon SQS        |

## Correct Answer

✅ **A. Amazon SNS**

## Why Correct?

SNS supports:

* SMS
* Email
* Push Notifications

## Why Others Are Wrong?

| Option | Reason             |
| ------ | ------------------ |
| B      | Email only         |
| C      | Monitoring service |
| D      | Queues messages    |

---

## Service: Amazon SNS

### Definition

Pub/Sub messaging service.

### Key Features

* SMS
* Email
* Push notifications

### Exam Traps

Notification = SNS

Queue = SQS

### Memory Trick

SNS = Shout to many people.

### Compare With

| Service | Purpose |
| ------- | ------- |
| SNS     | Notify  |
| SQS     | Queue   |

---

# Question 43 — Amazon Athena

## Question

A company has 5 TB of data stored in Amazon S3 and wants to occasionally run queries on the data in the most cost-effective way.

## Options

| Option | Service  |
| ------ | -------- |
| A      | Redshift |
| B      | Athena   |
| C      | Kinesis  |
| D      | RDS      |

## Correct Answer

✅ **B. Amazon Athena**

## Why Correct?

Athena queries S3 directly.

* No infrastructure
* Pay per query

## Why Others Are Wrong?

| Option | Reason              |
| ------ | ------------------- |
| A      | Data warehouse      |
| C      | Streaming service   |
| D      | Relational database |

---

## Service: Amazon Athena

### Definition

Serverless SQL query service for S3 data.

### Key Features

* Query S3 directly
* No servers
* Pay per query

### Exam Traps

Analyze S3 Data = Athena

### Memory Trick

Athena asks questions to S3.

### Compare With

| Service  | Purpose        |
| -------- | -------------- |
| Athena   | Query S3       |
| Redshift | Data Warehouse |

---

# Question 49 — Amazon CloudFront

## Question

A company is building an application that needs to deliver images and videos globally with minimal latency.

## Options

| Option | Service                     |
| ------ | --------------------------- |
| A      | Amazon CloudFront           |
| B      | S3 Cross-Region Replication |
| C      | VPN                         |
| D      | AWS PrivateLink             |

## Correct Answer

✅ **A. Amazon CloudFront**

## Why Correct?

### Keywords

* Global delivery
* Low latency
* Images
* Videos

CloudFront is AWS's Content Delivery Network (CDN).

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| B      | Replication is not a CDN |
| C      | Not content delivery     |
| D      | Private connectivity     |

---

## Service: Amazon CloudFront

### Definition

AWS Content Delivery Network (CDN).

### Key Features

* Edge locations
* Global delivery
* Reduced latency

### Exam Traps

Global Content Delivery = CloudFront

### Memory Trick

CloudFront puts content closer to users.

### Compare With

| Service    | Purpose |
| ---------- | ------- |
| CloudFront | CDN     |
| Route 53   | DNS     |

---

# Batch 03 Cheat Sheet

## 🔥 Top Services

* Reserved Instances
* AWS Direct Connect
* AWS Region
* Internet Gateway
* Amazon SNS
* Amazon Athena
* Amazon CloudFront

---

## 🔥 Top Facts To Memorize

| Concept                      | Remember           |
| ---------------------------- | ------------------ |
| Predictable workload         | Reserved Instances |
| Dedicated private connection | Direct Connect     |
| Geographic location          | Region             |
| Internet access in VPC       | Internet Gateway   |
| Notifications                | SNS                |
| Query S3 directly            | Athena             |
| Global content delivery      | CloudFront         |

---

## 🔥 Common Exam Traps

| Question Says        | Answer             |
| -------------------- | ------------------ |
| Dedicated Connection | Direct Connect     |
| Global CDN           | CloudFront         |
| Query S3             | Athena             |
| Notifications        | SNS                |
| Internet Access      | Internet Gateway   |
| Predictable Workload | Reserved Instances |

---

## 🔥 Most Likely To Reappear

1. Direct Connect vs VPN
2. SNS vs SQS
3. Athena vs Redshift
4. CloudFront vs Route 53
5. Reserved vs Spot vs On-Demand
