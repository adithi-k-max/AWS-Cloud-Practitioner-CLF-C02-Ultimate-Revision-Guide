# Top 100 AWS CLF-C02 Facts

This document contains 100 high-yield facts for the AWS Certified Cloud Practitioner (CLF-C02) exam.

The facts are organized by exam domain and are intended for rapid revision before the exam.

---

# Domain 1 — Cloud Concepts

## Fact 1

Cloud computing is the on-demand delivery of IT resources over the internet using pay-as-you-go pricing.

---

## Fact 2

The five main benefits of cloud computing are cost savings, agility, scalability, reliability, and global reach.

---

## Fact 3

Public Cloud infrastructure is owned and managed by a cloud provider such as AWS.

---

## Fact 4

Private Cloud infrastructure is dedicated to a single organization.

---

## Fact 5

Hybrid Cloud combines on-premises infrastructure with cloud resources.

---

## Fact 6

CAPEX (Capital Expenditure) refers to upfront investments such as purchasing servers and networking equipment.

---

## Fact 7

OPEX (Operational Expenditure) refers to ongoing operational costs such as AWS pay-as-you-go usage.

---

## Fact 8

Agility is the ability to rapidly acquire and deploy IT resources.

---

## Fact 9

Elasticity is the ability to automatically increase or decrease resources based on demand.

---

## Fact 10

Scalability is the ability of a system to handle increasing workloads.

---

## Fact 11

Vertical Scaling increases resources of an existing server.

Example:

4 GB RAM → 16 GB RAM

---

## Fact 12

Horizontal Scaling adds additional servers to handle more workload.

---

## Fact 13

Reliability is the ability of a workload to recover from failures and continue functioning correctly.

---

## Fact 14

High Availability minimizes downtime by using redundant resources across multiple Availability Zones.

---

## Fact 15

Fault Tolerance allows a workload to continue operating despite component failures.

---

## Fact 16

Durability refers to long-term data preservation.

Amazon S3 provides 99.999999999% durability.

---

## Fact 17

An AWS Region is a geographic area containing multiple Availability Zones.

---

## Fact 18

An Availability Zone consists of one or more data centers with independent power, cooling, and networking.

---

## Fact 19

Edge Locations are AWS sites used by CloudFront to deliver content closer to users.

---

## Fact 20

Local Zones extend AWS services closer to users for ultra-low latency workloads.

---

## Fact 21

AWS Cloud Adoption Framework (CAF) helps organizations adopt cloud technologies successfully.

---

## Fact 22

The six CAF perspectives are Business, People, Governance, Platform, Security, and Operations.

---

## Fact 23

The six Well-Architected Framework pillars are Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, and Sustainability.

---

## Fact 24

Rehost migration strategy is commonly called Lift and Shift.

---

## Fact 25

In the Shared Responsibility Model, AWS secures the cloud while customers secure their workloads in the cloud.

# Domain 2 — Security & Compliance

## Fact 26

AWS Identity and Access Management (IAM) enables secure control of access to AWS resources.

---

## Fact 27

IAM follows the principle of least privilege, meaning users should receive only the permissions necessary to perform their tasks.

---

## Fact 28

An IAM User represents an individual person or application that needs long-term AWS access.

---

## Fact 29

An IAM Group is a collection of IAM Users that share the same permissions.

---

## Fact 30

An IAM Role provides temporary permissions and is commonly used by AWS services such as EC2 and Lambda.

---

## Fact 31

Multi-Factor Authentication (MFA) adds an extra layer of security beyond a username and password.

---

## Fact 32

The AWS Root User has unrestricted access to all AWS resources and should be protected with MFA.

---

## Fact 33

AWS recommends avoiding daily use of the Root User account.

---

## Fact 34

AWS CloudTrail records API calls and account activity within an AWS environment.

---

## Fact 35

CloudTrail is primarily used for auditing, governance, and compliance.

---

## Fact 36

Amazon CloudWatch monitors AWS resources and applications using metrics, logs, and alarms.

---

## Fact 37

CloudWatch can automatically trigger alarms when specified thresholds are exceeded.

---

## Fact 38

AWS Config continuously assesses, audits, and evaluates AWS resource configurations.

---

## Fact 39

AWS Config helps organizations maintain compliance requirements.

---

## Fact 40

Amazon GuardDuty is AWS threat detection service.

---

## Fact 41

GuardDuty identifies suspicious activities, compromised credentials, and potential threats.

---

## Fact 42

Amazon Inspector performs automated vulnerability assessments.

---

## Fact 43

Inspector helps identify software vulnerabilities and missing security patches.

---

## Fact 44

Amazon Macie discovers and protects sensitive data stored in Amazon S3.

---

## Fact 45

Macie uses machine learning to identify personally identifiable information (PII).

---

## Fact 46

AWS Security Hub provides a centralized view of security findings across AWS services.

---

## Fact 47

Security Hub aggregates security alerts and compliance status into a single dashboard.

---

## Fact 48

AWS Key Management Service (KMS) is used to create and manage encryption keys.

---

## Fact 49

AWS Shield protects applications against Distributed Denial of Service (DDoS) attacks.

---

## Fact 50

AWS WAF helps protect web applications from common web exploits such as SQL Injection and Cross-Site Scripting (XSS).

# Domain 3 — Cloud Technology & Services

## Fact 51

Amazon EC2 provides resizable virtual servers in the cloud.

---

## Fact 52

EC2 instance types are optimized for different workloads such as compute, memory, storage, and networking.

---

## Fact 53

Auto Scaling automatically adds or removes EC2 instances based on demand.

---

## Fact 54

Elastic Load Balancing (ELB) distributes incoming traffic across multiple targets.

---

## Fact 55

AWS Lambda allows code execution without provisioning or managing servers.

---

## Fact 56

Lambda follows a serverless computing model and charges only for execution time.

---

## Fact 57

Amazon ECS is a fully managed container orchestration service.

---

## Fact 58

Amazon EKS is a managed Kubernetes service.

---

## Fact 59

AWS Fargate enables serverless container execution without managing servers.

---

## Fact 60

AWS Elastic Beanstalk automates application deployment and infrastructure provisioning.

---

## Fact 61

Amazon S3 is AWS object storage service.

---

## Fact 62

Amazon S3 stores data as objects inside buckets.

---

## Fact 63

Amazon S3 Glacier is designed for long-term archival storage.

---

## Fact 64

Amazon EBS provides persistent block storage for EC2 instances.

---

## Fact 65

Amazon EFS provides scalable shared file storage for multiple EC2 instances.

---

## Fact 66

AWS Storage Gateway connects on-premises environments to AWS storage services.

---

## Fact 67

AWS Snow Family devices help transfer large amounts of data into and out of AWS.

---

## Fact 68

Amazon RDS is a managed relational database service.

---

## Fact 69

Amazon Aurora is a high-performance relational database compatible with MySQL and PostgreSQL.

---

## Fact 70

Amazon DynamoDB is a fully managed NoSQL database service.

---

## Fact 71

Amazon DynamoDB delivers single-digit millisecond performance at virtually any scale.

---

## Fact 72

Amazon Redshift is AWS data warehouse service for analytics and reporting.

---

## Fact 73

Amazon ElastiCache improves application performance through in-memory caching.

---

## Fact 74

Amazon Neptune is AWS graph database service designed for highly connected datasets.

---

## Fact 75

Amazon VPC enables customers to create isolated virtual networks within AWS.

---

## Fact 76

A VPC can contain public and private subnets.

---

## Fact 77

Amazon Route 53 is AWS Domain Name System (DNS) service.

---

## Fact 78

Amazon CloudFront is AWS Content Delivery Network (CDN) service.

---

## Fact 79

AWS Direct Connect provides a dedicated private connection between an organization and AWS.

---

## Fact 80

A VPN creates an encrypted connection between on-premises environments and AWS.

---

## Fact 81

Amazon API Gateway enables the creation, publication, and management of APIs.

---

## Fact 82

Amazon SNS is a publish/subscribe messaging service used for notifications.

---

## Fact 83

Amazon SQS is a message queue service used to decouple applications.

---

## Fact 84

Amazon EventBridge is a serverless event bus used for event-driven architectures.

---

## Fact 85

Amazon Athena allows customers to query data stored in Amazon S3 using standard SQL without managing infrastructure.

# Domain 4 — Billing, Pricing & Support

## Fact 86

AWS follows a pay-as-you-go pricing model, allowing customers to pay only for the resources they consume.

---

## Fact 87

AWS Cost Explorer helps visualize, analyze, and forecast AWS spending and usage trends.

---

## Fact 88

AWS Budgets allows customers to set spending thresholds and receive alerts when limits are exceeded.

---

## Fact 89

AWS Pricing Calculator helps estimate AWS costs before deploying resources.

---

## Fact 90

AWS Compute Optimizer provides recommendations to rightsize AWS resources for cost and performance optimization.

---

## Fact 91

AWS Trusted Advisor provides recommendations based on AWS best practices for cost, security, performance, fault tolerance, and service limits.

---

## Fact 92

AWS Organizations helps centrally manage multiple AWS accounts from a single location.

---

## Fact 93

Consolidated Billing combines billing across multiple AWS accounts into a single bill.

---

## Fact 94

On-Demand pricing allows customers to pay for resources without long-term commitments.

---

## Fact 95

Reserved Instances provide discounted pricing in exchange for a one-year or three-year commitment.

---

## Fact 96

Spot Instances use spare AWS capacity and can provide the lowest compute costs, but they may be interrupted by AWS.

---

## Fact 97

Savings Plans provide flexible pricing discounts based on a commitment to consistent AWS usage over time.

---

## Fact 98

The Basic Support Plan is included with every AWS account at no additional cost.

---

## Fact 99

The Business Support Plan provides 24/7 technical support for production workloads.

---

## Fact 100

The Enterprise Support Plan includes a Technical Account Manager (TAM) and the highest level of AWS support.

---

# Top 100 AWS CLF-C02 Facts Complete

Coverage Summary

Domain 1 — Cloud Concepts

Facts 1–25

✅ Cloud Fundamentals

✅ Global Infrastructure

✅ CAF

✅ Well-Architected Framework

✅ Shared Responsibility Model

---

Domain 2 — Security & Compliance

Facts 26–50

✅ IAM

✅ Security Services

✅ Compliance

✅ Encryption

✅ Monitoring

---

Domain 3 — Cloud Technology & Services

Facts 51–85

✅ Compute

✅ Storage

✅ Databases

✅ Networking

✅ Messaging

✅ Analytics

---

Domain 4 — Billing, Pricing & Support

Facts 86–100

✅ Pricing Models

✅ Cost Management

✅ AWS Organizations

✅ Billing

✅ Support Plans

---

# Final Note

These 100 facts are designed as a high-yield revision resource for the AWS Certified Cloud Practitioner (CLF-C02) exam.

They are intended to reinforce core concepts, service identification, pricing models, security principles, and frequently tested exam topics.

Use this document together with:

- Domain Handbooks
- Service Comparisons
- Exam Traps
- Final Revision Sheet
- Practice Tests

for the best preparation experience.
