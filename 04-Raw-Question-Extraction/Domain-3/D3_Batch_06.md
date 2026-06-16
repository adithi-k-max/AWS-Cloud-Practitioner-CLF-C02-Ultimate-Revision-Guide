# DOMAIN 3 — BATCH 06

## Cloud Technology & Services

---

# Question 294 — Amazon S3 Intelligent-Tiering

## Question

Which Amazon S3 storage class is MOST cost-effective for unknown access patterns?

## Options

| Option | Storage Class          |
| ------ | ---------------------- |
| A      | S3 Standard            |
| B      | S3 Standard-IA         |
| C      | S3 One Zone-IA         |
| D      | S3 Intelligent-Tiering |

## Correct Answer

✅ **D. S3 Intelligent-Tiering**

## Why Correct?

### Keywords

* Unknown access patterns
* Cost optimization

Intelligent-Tiering automatically moves objects between storage tiers based on access patterns.

## Why Others Are Wrong?

| Option | Reason                                     |
| ------ | ------------------------------------------ |
| A      | Best for frequently accessed data          |
| B      | Assumes data is infrequently accessed      |
| C      | Less durable and assumes infrequent access |

---

## Service: Amazon S3 Intelligent-Tiering

### Definition

Automatically optimizes storage costs when access patterns are unknown.

### Key Features

* Automatic tier movement
* Cost optimization
* No performance impact

### Exam Traps

Unknown Access Pattern = Intelligent-Tiering

### Memory Trick

"Don't know usage? Let AWS decide."

### Compare With

| Storage Class       | Best Use Case           |
| ------------------- | ----------------------- |
| S3 Standard         | Frequent Access         |
| Standard-IA         | Infrequent Access       |
| One Zone-IA         | Infrequent + Lower Cost |
| Intelligent-Tiering | Unknown Access Pattern  |

---

# Question 596 — Amazon DynamoDB

## Question

Which AWS service is designed for users running workloads that include a NoSQL database?

## Options

| Option | Service         |
| ------ | --------------- |
| A      | Amazon RDS      |
| B      | Amazon S3       |
| C      | Amazon Redshift |
| D      | Amazon DynamoDB |

## Correct Answer

✅ **D. Amazon DynamoDB**

## Why Correct?

DynamoDB is AWS's fully managed NoSQL database.

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | Relational database      |
| B      | Object storage           |
| C      | Analytics data warehouse |

---

## Service: Amazon DynamoDB

### Definition

Fully managed NoSQL database.

### Key Features

* Key-value database
* Document database
* Serverless
* Millisecond latency

### Exam Traps

NoSQL = DynamoDB

### Memory Trick

DynamoDB = Dynamic NoSQL Database.

### Compare With

| Service  | Database Type  |
| -------- | -------------- |
| DynamoDB | NoSQL          |
| RDS      | Relational     |
| Aurora   | Relational     |
| Redshift | Data Warehouse |

---

# Question 597 — Amazon CloudFront

## Question

A company has a website on AWS. The company wants worldwide delivery and low-latency response.

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | AWS CloudFormation |
| B      | Amazon CloudFront  |
| C      | Amazon ElastiCache |
| D      | Amazon DynamoDB    |

## Correct Answer

✅ **B. Amazon CloudFront**

## Why Correct?

### Keywords

* Worldwide users
* Low latency

CloudFront is AWS's Content Delivery Network (CDN).

## Why Others Are Wrong?

| Option | Reason                            |
| ------ | --------------------------------- |
| A      | Infrastructure deployment service |
| C      | Caching service                   |
| D      | Database service                  |

---

## Service: Amazon CloudFront

### Definition

AWS Content Delivery Network (CDN).

### Key Features

* Edge locations
* Global caching
* Low latency
* Faster content delivery

### Exam Traps

Global Content Delivery = CloudFront

### Memory Trick

CloudFront = Content Close to Users.

---

# Question 598 — Amazon Lex

## Question

A company wants to add a conversational chatbot to its website.

## Options

| Option | Service            |
| ------ | ------------------ |
| A      | Amazon Textract    |
| B      | Amazon Lex         |
| C      | AWS Glue           |
| D      | Amazon Rekognition |

## Correct Answer

✅ **B. Amazon Lex**

## Why Correct?

Amazon Lex powers chatbots and conversational interfaces.

## Why Others Are Wrong?

| Option | Reason                       |
| ------ | ---------------------------- |
| A      | Extracts text from documents |
| C      | ETL service                  |
| D      | Image and video analysis     |

---

## Service: Amazon Lex

### Definition

AWS chatbot and conversational AI service.

### Key Features

* Natural Language Processing (NLP)
* Chatbots
* Voice bots
* Alexa technology

### Exam Traps

Chatbot = Amazon Lex

### Memory Trick

Lex = Alexa Technology for Your Applications.

### Compare With

| Service    | Purpose        |
| ---------- | -------------- |
| Lex        | Chatbots       |
| Polly      | Text-to-Speech |
| Transcribe | Speech-to-Text |

---

# Question 599 — Amazon CloudWatch

## Question

Which AWS service or feature can monitor potential disk write spikes on Amazon EC2?

## Options

| Option | Service              |
| ------ | -------------------- |
| A      | AWS CloudTrail       |
| B      | AWS Health Dashboard |
| C      | AWS Trusted Advisor  |
| D      | Amazon CloudWatch    |

## Correct Answer

✅ **D. Amazon CloudWatch**

## Why Correct?

CloudWatch monitors AWS resource metrics.

Disk activity is an EC2 metric monitored by CloudWatch.

## Why Others Are Wrong?

| Option | Reason                   |
| ------ | ------------------------ |
| A      | Audits API calls         |
| B      | Shows AWS service health |
| C      | Provides recommendations |

---

## Service: Amazon CloudWatch

### Definition

Monitoring and observability service.

### Key Features

* Metrics
* Alarms
* Dashboards
* Logs

### Exam Traps

Monitor Performance = CloudWatch

CloudTrail = Audit Logs

### Memory Trick

Watch = Monitor

### Compare With

| Service         | Purpose         |
| --------------- | --------------- |
| CloudWatch      | Monitoring      |
| CloudTrail      | Auditing        |
| Trusted Advisor | Recommendations |

---

# Question 600 — AWS Outposts

## Question

A company has applications controlling factory equipment on premises.

The company wants the least latency.

## Options

| Option | Service      |
| ------ | ------------ |
| A      | AWS Outposts |
| B      | Amazon EC2   |
| C      | AWS Lambda   |
| D      | AWS Fargate  |

## Correct Answer

✅ **A. AWS Outposts**

## Why Correct?

### Keywords

* On-premises
* Lowest latency
* Local processing

Outposts brings AWS infrastructure directly into customer facilities.

## Why Others Are Wrong?

| Option | Reason              |
| ------ | ------------------- |
| B      | Runs in AWS Regions |
| C      | Runs in AWS Regions |
| D      | Runs in AWS Regions |

---

## Service: AWS Outposts

### Definition

AWS infrastructure installed in customer facilities.

### Key Features

* Hybrid cloud
* Local processing
* Low latency
* AWS services on-premises

### Exam Traps

AWS Services On-Premises = Outposts

### Memory Trick

Outpost = AWS Outside AWS.

### Compare With

| Service     | Purpose                 |
| ----------- | ----------------------- |
| Outposts    | AWS On-Premises         |
| Local Zones | AWS Near Users          |
| Regions     | AWS Core Infrastructure |

---

# Batch 06 Cheat Sheet

## 🔥 Top Services

* Amazon S3 Intelligent-Tiering
* Amazon DynamoDB
* Amazon CloudFront
* Amazon Lex
* Amazon CloudWatch
* AWS Outposts

---

## 🔥 Top Facts To Memorize

| Concept                  | Remember            |
| ------------------------ | ------------------- |
| Unknown Access Pattern   | Intelligent-Tiering |
| NoSQL Database           | DynamoDB            |
| Global Content Delivery  | CloudFront          |
| Chatbot Service          | Amazon Lex          |
| Monitoring               | CloudWatch          |
| AWS Hardware On-Premises | Outposts            |

---

## 🔥 Common Exam Traps

| Question Says           | Answer              |
| ----------------------- | ------------------- |
| Unknown Storage Pattern | Intelligent-Tiering |
| Chatbot                 | Lex                 |
| Monitor EC2 Metrics     | CloudWatch          |
| Global CDN              | CloudFront          |
| NoSQL                   | DynamoDB            |
| AWS Hardware On-Site    | Outposts            |

---

## 🔥 Most Likely To Reappear

1. CloudWatch vs CloudTrail
2. Lex vs Polly
3. DynamoDB vs RDS
4. CloudFront vs Route 53
5. Outposts vs Local Zones
