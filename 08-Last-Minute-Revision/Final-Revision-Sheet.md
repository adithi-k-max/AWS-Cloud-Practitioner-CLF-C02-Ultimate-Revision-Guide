# AWS CLF-C02 Final Revision Sheet

This document is designed for rapid revision before the AWS Certified Cloud Practitioner (CLF-C02) exam.

If you have limited time, focus on the concepts, service mappings, comparisons, and exam traps listed below.

---

# Domain 1 — Cloud Concepts

## Cloud Deployment Models

Public Cloud

* AWS owns and manages infrastructure
* Pay-as-you-go pricing

Private Cloud

* Dedicated to one organization
* Greater control

Hybrid Cloud

* Combination of cloud and on-premises infrastructure

---

## Core Concepts

Agility

* Ability to innovate quickly
* Rapid deployment of resources

Elasticity

* Automatically increase and decrease resources based on demand

Scalability

* Ability to handle increasing workloads

Reliability

* Ability to recover from failures

High Availability

* Minimize downtime using multiple Availability Zones

Fault Tolerance

* Continue operating despite failures

Durability

* Long-term data protection

---

## CAPEX vs OPEX

CAPEX

* Buy hardware
* Large upfront investment

OPEX

* Pay-as-you-go
* Cloud spending model

---

## AWS Global Infrastructure

Region

* Geographic location

Availability Zone

* One or more data centers

Edge Location

* Content delivery location

Local Zone

* Low-latency AWS extension

---

## CAF Perspectives

* Business
* People
* Governance
* Platform
* Security
* Operations

---

## Well-Architected Framework Pillars

* Operational Excellence
* Security
* Reliability
* Performance Efficiency
* Cost Optimization
* Sustainability

---

# Domain 2 — Security & Compliance

## IAM

IAM User

* Human identity

IAM Role

* Temporary permissions

MFA

* Additional security layer

Least Privilege

* Minimum permissions required

---

## Security Services

CloudTrail

* Audit logs
* API calls

CloudWatch

* Monitoring
* Metrics
* Alarms

GuardDuty

* Threat detection

Inspector

* Vulnerability assessment

Macie

* Sensitive data discovery

Security Hub

* Central security dashboard

KMS

* Encryption key management

---

## Protection Services

WAF

* Web application firewall

Shield

* DDoS protection

---

## Shared Responsibility Model

AWS Responsibilities

* Physical hardware
* Data centers
* Networking infrastructure

Customer Responsibilities

* IAM permissions
* Customer data
* Security groups
* Operating systems on EC2

---

# Domain 3 — Cloud Technology & Services

## Compute

EC2

* Virtual servers

Lambda

* Serverless compute

ECS

* Containers

EKS

* Kubernetes

Fargate

* Serverless containers

Elastic Beanstalk

* Application deployment

Auto Scaling

* Automatic scaling

Elastic Load Balancer

* Traffic distribution

---

## Storage

S3

* Object storage

EBS

* Block storage

EFS

* File storage

S3 Glacier

* Archive storage

Storage Gateway

* Hybrid storage

Snow Family

* Data transfer devices

---

## Databases

RDS

* Relational database

Aurora

* High-performance relational database

DynamoDB

* NoSQL database

Redshift

* Data warehouse

Neptune

* Graph database

ElastiCache

* In-memory cache

---

## Networking

VPC

* Private network

Route 53

* DNS

CloudFront

* CDN

Direct Connect

* Dedicated connection

VPN

* Secure encrypted tunnel

API Gateway

* API management

---

## Messaging

SNS

* Notifications

SQS

* Message queue

EventBridge

* Event routing

---

## Analytics

Athena

* Query S3 using SQL

Kinesis

* Streaming data

EMR

* Big data processing

QuickSight

* Dashboards

---

## AI & ML

Rekognition

* Image analysis

Comprehend

* Text analysis

Lex

* Chatbots

Polly

* Text to speech

Textract

* Extract text from documents

Translate

* Language translation

Transcribe

* Speech to text

---

# Domain 4 — Billing, Pricing & Support

## Cost Management

Cost Explorer

* Analyze spending

AWS Budgets

* Cost alerts

Pricing Calculator

* Future cost estimates

Compute Optimizer

* Rightsizing

Trusted Advisor

* AWS recommendations

---

## Organizations

AWS Organizations

* Multi-account management

Consolidated Billing

* Single bill across accounts

---

## Pricing Models

On-Demand

* No commitment

Reserved Instances

* Predictable workloads

Spot Instances

* Lowest cost
* Interruptible

Savings Plans

* Flexible long-term savings

---

## Support Plans

Basic

* Free support

Developer

* Business-hours support

Business

* 24/7 support

Enterprise

* Technical Account Manager (TAM)

---

# Most Important Comparisons

CloudTrail vs CloudWatch

* Audit vs Monitoring

GuardDuty vs Inspector

* Threat Detection vs Vulnerability Assessment

SNS vs SQS

* Notifications vs Queue

WAF vs Shield

* Web Protection vs DDoS Protection

EBS vs EFS vs S3

* Block vs File vs Object Storage

DynamoDB vs Redshift vs Neptune

* NoSQL vs Data Warehouse vs Graph Database

IAM User vs IAM Role

* Human Identity vs Temporary Permissions

Reserved vs Spot vs Savings Plans

* Predictable vs Cheapest vs Flexible Savings

---

# Most Common Exam Traps

Move Fast

→ Agility

Automatically Scale

→ Elasticity

Handle Growth

→ Scalability

Recover From Failure

→ Reliability

Multiple AZs

→ High Availability

Continue During Failure

→ Fault Tolerance

Threat Detection

→ GuardDuty

Vulnerability Scan

→ Inspector

Audit Logs

→ CloudTrail

Monitoring

→ CloudWatch

DNS

→ Route 53

CDN

→ CloudFront

Object Storage

→ S3

NoSQL

→ DynamoDB

Data Warehouse

→ Redshift

Notifications

→ SNS

Queue Messages

→ SQS

Web Application Firewall

→ WAF

DDoS Protection

→ Shield

---

# Exam-Day Strategy

Read the question carefully.

Identify AWS keywords.

Eliminate obviously incorrect answers.

Compare the remaining options.

Choose the service that best fits the scenario.

Do not rush.

Many questions can be solved through elimination alone.

---

# Final Memory Check

Can you instantly identify:

* EC2
* Lambda
* S3
* EBS
* EFS
* DynamoDB
* RDS
* Route 53
* CloudFront
* SNS
* SQS
* IAM
* CloudTrail
* CloudWatch
* GuardDuty
* Inspector
* WAF
* Shield
* Cost Explorer
* AWS Budgets

If yes, you are well prepared for the AWS Certified Cloud Practitioner (CLF-C02) exam.
