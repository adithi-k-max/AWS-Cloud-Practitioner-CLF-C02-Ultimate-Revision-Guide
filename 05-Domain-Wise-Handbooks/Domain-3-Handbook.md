# Domain 3 Handbook — Cloud Technology & Services (CLF-C02)

---

# Overview

Domain 3 contributes approximately 34% of the AWS Certified Cloud Practitioner (CLF-C02) exam.

This is the largest domain in the exam and focuses on AWS services.

This domain covers:

- Compute Services
- Storage Services
- Networking Services
- Database Services
- Containers
- Serverless
- Monitoring
- Migration
- Content Delivery
- Messaging
- Analytics
- Machine Learning

Unlike Domain 1 and Domain 2, Domain 3 is heavily service-based.

Success in this domain depends on:

- Service recognition
- Use case identification
- Service comparisons
- Exam trap elimination

---

# Chapter 1 — Amazon EC2

## Definition

Amazon Elastic Compute Cloud (EC2) provides virtual servers in the cloud.

---

## Purpose

Run applications without purchasing physical hardware.

---

## Common Use Cases

- Web applications
- Enterprise applications
- Databases
- Application hosting
- Custom workloads

---

## Benefits

- Full server control
- Flexible sizing
- Multiple operating systems
- Pay-as-you-go pricing

---

## Exam Keywords

- Virtual Server
- Compute
- Operating System
- Server Hosting

Answer:

✅ Amazon EC2

---

## Memory Trick

EC2 = Computer in AWS

---

# Chapter 2 — EC2 Instance Types

AWS provides different instance families optimized for different workloads.

---

## General Purpose

Balanced:

- CPU
- Memory
- Networking

Example:

- T3
- T4g

Use Cases:

- Web servers
- Small databases

---

## Compute Optimized

High CPU performance.

Example:

- C5
- C6

Use Cases:

- Scientific computing
- Gaming servers
- Batch processing

---

## Memory Optimized

Large RAM capacity.

Example:

- R5
- X1

Use Cases:

- In-memory databases
- Analytics

---

## Storage Optimized

High disk performance.

Example:

- I3
- D2

Use Cases:

- Data warehousing
- Big data

---

## Accelerated Computing

GPU-enabled instances.

Use Cases:

- Machine Learning
- AI Training
- Graphics Rendering

---

## Exam Trap

Question Says:

- GPU
- Graphics Processing
- Machine Learning

Answer:

✅ Accelerated Computing

---

# Chapter 3 — EC2 Pricing Models

AWS frequently tests pricing options.

---

## On-Demand Instances

Pay for usage.

No commitment.

Best For:

- Short-term workloads
- Unpredictable workloads

---

## Reserved Instances

Commitment:

- 1 Year
- 3 Years

Benefits:

- Significant discounts

Best For:

- Predictable workloads

---

## Spot Instances

Unused AWS capacity.

Benefits:

- Up to 90% discount

Limitation:

- Can be interrupted

Best For:

- Fault-tolerant workloads
- Batch processing

---

## Dedicated Hosts

Physical servers dedicated to one customer.

Best For:

- Licensing requirements
- Compliance

---

## Exam Trap

Question Says:

- Interruptible workload
- Lowest cost

Answer:

✅ Spot Instances

---

Question Says:

- Predictable workload

Answer:

✅ Reserved Instances

---

# Chapter 4 — Auto Scaling

## Definition

Automatically adjusts EC2 capacity based on demand.

---

## Purpose

Maintain performance while reducing costs.

---

## Benefits

- Automatic scaling
- Cost optimization
- High availability

---

## Example

Traffic increases:

More EC2 instances launched.

Traffic decreases:

Extra instances terminated.

---

## Exam Keywords

- Automatic Scaling
- Capacity Adjustment
- Dynamic Scaling

Answer:

✅ Auto Scaling

---

# Chapter 5 — Elastic Load Balancer (ELB)

## Definition

Distributes incoming traffic across multiple targets.

---

## Supported Targets

- EC2
- Containers
- IP Addresses
- Lambda

---

## Benefits

- High Availability
- Fault Tolerance
- Traffic Distribution

---

## Example

1000 users visit application.

ELB distributes traffic among multiple servers.

---

## Exam Keywords

- Traffic Distribution
- Multiple Servers
- High Availability

Answer:

✅ Elastic Load Balancer

---

## Memory Trick

Load Balancer = Traffic Police

---

# Chapter 6 — AWS Lambda

## Definition

Serverless compute service.

Run code without managing servers.

---

## Benefits

- No server management
- Automatic scaling
- Pay per execution

---

## Use Cases

- APIs
- Automation
- Event processing
- File processing

---

## Exam Keywords

- Run Code
- No Servers
- Event Driven

Answer:

✅ AWS Lambda

---

## Memory Trick

Lambda = Functions Only

No Servers

---

# Chapter 7 — Amazon Lightsail

## Definition

Simplified cloud platform for beginners.

---

## Purpose

Easy website and application deployment.

---

## Includes

- Compute
- Storage
- Networking

---

## Benefits

- Simple pricing
- Beginner friendly
- Easy setup

---

## Exam Keywords

- Beginner Developer
- Simple Hosting
- VPS

Answer:

✅ Amazon Lightsail

---

## Exam Trap

Beginner AWS User

Answer:

✅ Lightsail

Not:

❌ EC2

---

# Chapter 8 — Containers Overview

## Definition

Containers package:

- Application
- Dependencies
- Runtime

into a portable unit.

---

## Benefits

- Portability
- Consistency
- Fast deployment

---

## Container Services

- ECS
- EKS
- Fargate

---

# Chapter 9 — Amazon ECS

## Definition

Amazon Elastic Container Service.

Container orchestration service.

---

## Purpose

Run Docker containers.

---

## Benefits

- Managed service
- AWS integration
- Scalable

---

## Exam Keywords

- Containers
- Docker
- Orchestration

Answer:

✅ ECS

---

# Chapter 10 — Amazon EKS

## Definition

Amazon Elastic Kubernetes Service.

Managed Kubernetes.

---

## Purpose

Run Kubernetes workloads.

---

## Benefits

- Managed Kubernetes
- High Availability
- Scalability

---

## Exam Keywords

- Kubernetes
- Container Orchestration

Answer:

✅ EKS

---

# Chapter 11 — AWS Fargate

## Definition

Serverless compute engine for containers.

---

## Works With

- ECS
- EKS

---

## Benefits

- No server management
- Automatic scaling
- Container execution

---

## Exam Keywords

- Containers
- No Servers

Answer:

✅ AWS Fargate

---

## Exam Trap

Question Says:

Containers without managing servers

Answer:

✅ Fargate

---

# Chapter 12 — Compute Services Comparison

| Service | Purpose |
|----------|----------|
| EC2 | Virtual Servers |
| Lambda | Serverless Functions |
| Lightsail | Simplified Hosting |
| ECS | Container Orchestration |
| EKS | Kubernetes |
| Fargate | Serverless Containers |

---

# Chapter 13 — Most Common Compute Exam Traps

| Question Says | Answer |
|--------------|---------|
| Virtual Server | EC2 |
| Run Code Without Servers | Lambda |
| Beginner Hosting | Lightsail |
| Docker Containers | ECS |
| Kubernetes | EKS |
| Containers Without Servers | Fargate |
| GPU Workload | Accelerated Computing |
| Interruptible Compute | Spot Instances |
| Predictable Workload | Reserved Instances |
| Automatic Capacity Adjustment | Auto Scaling |
| Traffic Distribution | Load Balancer |

---

# Chapter 14 — Compute Final Revision Sheet

Know these instantly:

- EC2
- EC2 Instance Types
- General Purpose
- Compute Optimized
- Memory Optimized
- Storage Optimized
- Accelerated Computing
- On-Demand
- Reserved Instances
- Spot Instances
- Dedicated Hosts
- Auto Scaling
- Elastic Load Balancer
- Lambda
- Lightsail
- Containers
- ECS
- EKS
- Fargate

---

# Chapter 15 — Amazon S3

## Definition

Amazon Simple Storage Service (S3) is AWS's object storage service.

---

## Purpose

Store and retrieve any amount of data from anywhere.

---

## Common Use Cases

- Website assets
- Images
- Videos
- Backups
- Data lakes
- Static website hosting

---

## Benefits

- Highly scalable
- Highly durable
- Secure
- Cost effective

---

## Key Features

- Object Storage
- Versioning
- Lifecycle Policies
- Encryption
- Cross-Region Replication

---

## Exam Keywords

- Object Storage
- Unlimited Storage
- Static Website
- Store Files

Answer:

✅ Amazon S3

---

## Memory Trick

S3 = Store Stuff Simply

---

# Chapter 16 — Amazon S3 Storage Classes

AWS provides multiple storage classes for different access patterns.

---

## S3 Standard

For frequently accessed data.

### Features

- High availability
- Low latency
- Immediate access

### Use Cases

- Websites
- Applications
- Frequently used data

---

## S3 Standard-IA

Infrequent Access storage.

### Features

- Lower storage cost
- Immediate retrieval

### Use Cases

- Backups
- Rarely accessed files

---

### Exam Trap

Question Says:

- Rare access
- Immediate retrieval

Answer:

✅ S3 Standard-IA

---

## S3 One Zone-IA

Stores data in a single Availability Zone.

### Benefits

- Lower cost

### Limitation

- Less resilient

---

## S3 Glacier Instant Retrieval

Archive storage with immediate retrieval.

### Use Cases

- Archived data requiring fast access

---

## S3 Glacier Flexible Retrieval

Archive storage with retrieval delays.

### Use Cases

- Long-term archives

---

## S3 Glacier Deep Archive

Lowest-cost storage class.

### Use Cases

- Compliance archives
- Long-term retention

### Retrieval Time

Several hours

---

### Exam Trap

Question Says:

- Long-term archive
- Lowest cost

Answer:

✅ Glacier Deep Archive

---

## S3 Intelligent-Tiering

Automatically moves data between tiers.

### Benefits

- Cost optimization
- Automatic tier selection

---

# Chapter 17 — Amazon EBS

## Definition

Amazon Elastic Block Store (EBS) provides block storage for EC2.

---

## Purpose

Persistent storage for EC2 instances.

---

## Benefits

- High performance
- Persistent storage
- Snapshot support

---

## Use Cases

- Operating system disks
- Databases
- Applications

---

## Exam Keywords

- EC2 Disk
- Block Storage
- Persistent Volume

Answer:

✅ Amazon EBS

---

## Memory Trick

EBS = EC2 Hard Drive

---

# Chapter 18 — EBS Snapshots

## Definition

Point-in-time backup of an EBS volume.

---

## Benefits

- Incremental backups
- Disaster recovery
- Fast restoration

---

## Use Cases

- Backup
- Recovery
- Migration

---

## Exam Keywords

- Backup EBS
- One-time Backup
- Restore Volume

Answer:

✅ EBS Snapshot

---

## Memory Trick

Snapshot = Save Game

---

# Chapter 19 — Amazon EFS

## Definition

Amazon Elastic File System (EFS) is a managed file storage service.

---

## Purpose

Provide shared storage for multiple EC2 instances.

---

## Benefits

- Shared access
- Automatic scaling
- Managed service

---

## Use Cases

- Shared application storage
- Content management systems
- Multi-instance applications

---

## Exam Keywords

- Shared File Storage
- Multiple EC2 Instances
- Linux File System

Answer:

✅ Amazon EFS

---

## Memory Trick

EFS = Elastic File System

---

# Chapter 20 — Amazon FSx

## Definition

Fully managed file systems optimized for specific workloads.

---

## Variants

### FSx for Windows File Server

Provides Windows-native file storage.

---

### FSx for Lustre

High-performance file system.

Used for:

- Machine Learning
- HPC
- Analytics

---

### FSx for NetApp ONTAP

Enterprise storage workloads.

---

### FSx for OpenZFS

Linux-based file storage.

---

## Exam Keywords

- Windows File Share
- High Performance File System

Answer:

✅ Amazon FSx

---

# Chapter 21 — Storage Services Comparison

| Service | Storage Type |
|----------|-------------|
| S3 | Object Storage |
| EBS | Block Storage |
| EFS | File Storage |
| FSx | Specialized File Storage |

---

## Exam Trap

Question Says:

Store Objects

Answer:

✅ S3

---

Question Says:

EC2 Disk

Answer:

✅ EBS

---

Question Says:

Shared File System

Answer:

✅ EFS

---

Question Says:

Windows File Share

Answer:

✅ FSx

---

# Chapter 22 — AWS Backup

## Definition

Centralized backup service for AWS resources.

---

## Purpose

Manage backups from one location.

---

## Supported Services

- EBS
- EFS
- RDS
- DynamoDB
- Storage Gateway

---

## Benefits

- Centralized management
- Automation
- Compliance support

---

## Exam Keywords

- Centralized Backup
- Backup Management

Answer:

✅ AWS Backup

---

# Chapter 23 — AWS Storage Gateway

## Definition

Hybrid storage service connecting on-premises storage to AWS.

---

## Purpose

Integrate on-premises environments with AWS storage.

---

## Benefits

- Hybrid cloud
- Local access
- Cloud scalability

---

## Use Cases

- Backup
- Disaster recovery
- Hybrid storage

---

## Exam Keywords

- Hybrid Storage
- On-Premises Integration

Answer:

✅ Storage Gateway

---

## Memory Trick

Storage Gateway = Bridge to AWS Storage

---

# Chapter 24 — AWS Snow Family

## Definition

Physical devices used to transfer data into and out of AWS.

---

## Purpose

Move large amounts of data when network transfer is impractical.

---

# Chapter 25 — AWS Snowcone

## Definition

Smallest Snow Family device.

---

## Benefits

- Portable
- Lightweight

---

## Use Cases

- Edge locations
- Remote sites

---

# Chapter 26 — AWS Snowball Edge

## Definition

Large-capacity migration device.

---

## Benefits

- Data migration
- Edge computing

---

## Use Cases

- Petabyte-scale transfers

---

# Chapter 27 — AWS Snowmobile

## Definition

Exabyte-scale data transfer solution.

---

## Characteristics

Physical truck used for migration.

---

## Use Cases

- Massive migrations

---

## Exam Trap

Question Says:

- Petabytes
- Large migration
- Physical device

Answer:

✅ Snowball Edge

---

Question Says:

- Exabytes
- Massive migration

Answer:

✅ Snowmobile

---

# Chapter 28 — AWS DataSync

## Definition

Online data transfer service.

---

## Purpose

Transfer large datasets between:

- On-premises
- AWS

---

## Supported Destinations

- S3
- EFS
- FSx

---

## Benefits

- High-speed transfer
- Automation
- Secure migration

---

## Exam Keywords

- Millions of Files
- Large Dataset Migration
- File Transfer

Answer:

✅ AWS DataSync

---

## Memory Trick

DataSync = Sync Data Quickly

---

## Exam Trap

Question Says:

File Migration

Answer:

✅ DataSync

---

Question Says:

Database Migration

Answer:

❌ Not DataSync

✅ AWS DMS

---

# Chapter 29 — AWS Transfer Family

## Definition

Managed file transfer service.

---

## Supported Protocols

- SFTP
- FTPS
- FTP

---

## Purpose

Transfer files into AWS securely.

---

## Use Cases

- Business file exchanges
- Partner integrations

---

## Exam Keywords

- Managed SFTP
- Secure File Transfer

Answer:

✅ AWS Transfer Family

---

# Chapter 30 — Storage & Data Transfer Mega Comparison

| Service | Purpose |
|----------|----------|
| S3 | Object Storage |
| EBS | Block Storage |
| EFS | Shared File Storage |
| FSx | Specialized File Systems |
| EBS Snapshot | EBS Backup |
| Backup | Centralized Backup |
| Storage Gateway | Hybrid Storage |
| Snowcone | Small Offline Transfer |
| Snowball Edge | Large Offline Transfer |
| Snowmobile | Massive Offline Transfer |
| DataSync | Online File Migration |
| Transfer Family | Managed FTP/SFTP |

---

# Chapter 31 — Most Common Storage Exam Traps

| Question Says | Answer |
|--------------|---------|
| Object Storage | S3 |
| Frequently Accessed Data | S3 Standard |
| Rare Access + Immediate Retrieval | S3 Standard-IA |
| Archive Storage | Glacier |
| Lowest Cost Archive | Glacier Deep Archive |
| Automatic Tier Selection | Intelligent-Tiering |
| EC2 Disk | EBS |
| Backup EBS | Snapshot |
| Shared File System | EFS |
| Windows File Share | FSx |
| Centralized Backup | AWS Backup |
| Hybrid Storage | Storage Gateway |
| Millions of Files Migration | DataSync |
| Petabyte Migration | Snowball Edge |
| Exabyte Migration | Snowmobile |
| Managed SFTP | Transfer Family |

---

# Chapter 32 — Storage Final Revision Sheet

Know these instantly:

- S3
- S3 Standard
- S3 Standard-IA
- S3 One Zone-IA
- Glacier Instant Retrieval
- Glacier Flexible Retrieval
- Glacier Deep Archive
- Intelligent-Tiering
- EBS
- EBS Snapshots
- EFS
- FSx
- AWS Backup
- Storage Gateway
- Snowcone
- Snowball Edge
- Snowmobile
- DataSync
- Transfer Family

---

# Chapter 33 — Amazon VPC

## Definition

Amazon Virtual Private Cloud (VPC) is a logically isolated virtual network within AWS.

---

## Purpose

Launch AWS resources in a private network.

---

## Benefits

- Isolation
- Security
- Custom networking
- Full control over IP addressing

---

## Components

- Subnets
- Route Tables
- Internet Gateway
- NAT Gateway
- Security Groups
- Network ACLs

---

## Exam Keywords

- Private AWS Network
- Isolated Network
- Virtual Network

Answer:

✅ Amazon VPC

---

## Memory Trick

VPC = Your Private AWS Network

---

# Chapter 34 — Subnets

## Definition

A subnet is a portion of a VPC.

---

## Types

### Public Subnet

Can communicate with the internet.

Examples:

- Web servers
- Load Balancers

---

### Private Subnet

No direct internet access.

Examples:

- Databases
- Internal applications

---

## Exam Trap

Question Says:

Internet-facing resources

Answer:

✅ Public Subnet

---

Question Says:

Database layer

Answer:

✅ Private Subnet

---

# Chapter 35 — Route Tables

## Definition

Route tables determine where network traffic is sent.

---

## Purpose

Control network routing.

---

## Example

Traffic destined for internet:

Sent to Internet Gateway.

---

## Benefits

- Traffic management
- Connectivity control

---

## Exam Keywords

- Traffic Routing
- Network Path

Answer:

✅ Route Table

---

# Chapter 36 — Internet Gateway

## Definition

Allows communication between a VPC and the internet.

---

## Purpose

Provide internet connectivity.

---

## Requirements

- Attached to VPC
- Public subnet route

---

## Exam Keywords

- Internet Access
- Public Connectivity

Answer:

✅ Internet Gateway

---

## Memory Trick

Internet Gateway = Door to the Internet

---

# Chapter 37 — NAT Gateway

## Definition

Allows private subnet resources to access the internet.

---

## Purpose

Outbound internet access.

---

## Example

Private EC2 downloads updates.

Internet can NOT initiate connections back.

---

## Benefits

- Security
- Controlled internet access

---

## Exam Keywords

- Private Subnet Internet Access
- Outbound Connectivity

Answer:

✅ NAT Gateway

---

## Exam Trap

Question Says:

Private resources need internet access

Answer:

✅ NAT Gateway

---

# Chapter 38 — Security Groups

## Definition

Instance-level virtual firewall.

---

## Scope

Attached directly to:

- EC2 Instances
- Load Balancers
- Other AWS resources

---

## Characteristics

- Stateful
- Allow Rules Only

---

## Benefits

- Traffic filtering
- Resource protection

---

## Exam Keywords

- EC2 Firewall
- Instance Security
- Port Access

Answer:

✅ Security Group

---

## Memory Trick

Security Group = House Security

---

# Chapter 39 — Network ACL (NACL)

## Definition

Subnet-level virtual firewall.

---

## Characteristics

- Stateless
- Allow Rules
- Deny Rules
- Rule Order Matters

---

## Benefits

- Subnet protection
- Additional network security

---

## Exam Keywords

- Subnet Firewall
- Deny Traffic
- Stateless

Answer:

✅ Network ACL

---

## Memory Trick

NACL = Neighborhood Firewall

---

# Chapter 40 — Security Group vs NACL

| Feature | Security Group | NACL |
|----------|---------------|------|
| Scope | Instance | Subnet |
| Stateful | Yes | No |
| Allow Rules | Yes | Yes |
| Deny Rules | No | Yes |
| Rule Order | No | Yes |

---

## Exam Trap

Question Says:

Instance Firewall

Answer:

✅ Security Group

---

Question Says:

Subnet Firewall

Answer:

✅ NACL

---

Question Says:

Stateless

Answer:

✅ NACL

---

Question Says:

Stateful

Answer:

✅ Security Group

---

# Chapter 41 — Amazon Route 53

## Definition

AWS DNS service.

---

## Purpose

Route users to AWS resources.

---

## Features

- Domain Registration
- DNS Routing
- Health Checks

---

## Benefits

- Highly available
- Scalable
- Global service

---

## Exam Keywords

- DNS
- Domain Name
- Route Traffic

Answer:

✅ Route 53

---

## Memory Trick

Route Traffic = Route 53

---

# Chapter 42 — Amazon CloudFront

## Definition

AWS Content Delivery Network (CDN).

---

## Purpose

Deliver content closer to users.

---

## Benefits

- Low latency
- Faster performance
- Global delivery

---

## Uses

- Websites
- Videos
- Static content
- APIs

---

## Exam Keywords

- Global Content Delivery
- Low Latency
- CDN

Answer:

✅ CloudFront

---

## Memory Trick

CloudFront = Front Door Near Users

---

# Chapter 43 — Edge Locations

## Definition

Global locations used by CloudFront.

---

## Purpose

Cache content near users.

---

## Benefits

- Reduced latency
- Faster content delivery

---

## Exam Keywords

- Cache Near Users
- Global Delivery

Answer:

✅ Edge Location

---

# Chapter 44 — AWS Direct Connect

## Definition

Dedicated private connection between AWS and on-premises environments.

---

## Benefits

- Consistent performance
- Reduced latency
- Private connectivity

---

## Uses

- Enterprise networking
- Hybrid cloud

---

## Exam Keywords

- Dedicated Connection
- Private Link
- No Public Internet

Answer:

✅ AWS Direct Connect

---

## Memory Trick

Direct Connect = Private Highway to AWS

---

# Chapter 45 — AWS Site-to-Site VPN

## Definition

Encrypted connection between AWS and on-premises environments.

---

## Characteristics

- Uses internet
- Fast setup
- Secure tunnel

---

## Benefits

- Low cost
- Quick deployment

---

## Exam Keywords

- Secure Connection
- Fast Setup
- VPN Tunnel

Answer:

✅ Site-to-Site VPN

---

## Exam Trap

Question Says:

Quick setup

Answer:

✅ VPN

---

Question Says:

Dedicated connection

Answer:

✅ Direct Connect

---

# Chapter 46 — AWS Transit Gateway

## Definition

Central hub connecting multiple networks.

---

## Purpose

Simplify network architecture.

---

## Connects

- VPCs
- VPNs
- Direct Connect

---

## Benefits

- Centralized connectivity
- Simplified routing

---

## Exam Keywords

- Network Hub
- Connect Multiple VPCs

Answer:

✅ Transit Gateway

---

## Memory Trick

Transit Gateway = Network Router for AWS

---

# Chapter 47 — AWS Outposts

## Definition

AWS infrastructure installed in customer data centers.

---

## Purpose

Run AWS services on-premises.

---

## Benefits

- Low latency
- Hybrid cloud
- Consistent AWS experience

---

## Use Cases

- Factory systems
- Local processing
- Regulatory requirements

---

## Exam Keywords

- AWS On-Premises
- Local AWS Infrastructure
- Lowest Latency

Answer:

✅ AWS Outposts

---

## Memory Trick

Outposts = AWS Inside Your Building

---

# Chapter 48 — Networking Services Comparison

| Service | Purpose |
|----------|----------|
| VPC | Private AWS Network |
| Public Subnet | Internet-Facing Resources |
| Private Subnet | Internal Resources |
| Route Table | Traffic Routing |
| Internet Gateway | Internet Access |
| NAT Gateway | Private Subnet Internet Access |
| Security Group | Instance Firewall |
| NACL | Subnet Firewall |
| Route 53 | DNS |
| CloudFront | CDN |
| Direct Connect | Dedicated Private Connection |
| VPN | Secure Internet Connection |
| Transit Gateway | Network Hub |
| Outposts | AWS On-Premises |

---

# Chapter 49 — Most Common Networking Exam Traps

| Question Says | Answer |
|--------------|---------|
| Private AWS Network | VPC |
| Internet Facing | Public Subnet |
| Database Layer | Private Subnet |
| Internet Access | Internet Gateway |
| Private Internet Access | NAT Gateway |
| Instance Firewall | Security Group |
| Subnet Firewall | NACL |
| Stateful Firewall | Security Group |
| Stateless Firewall | NACL |
| DNS Service | Route 53 |
| Domain Registration | Route 53 |
| Global CDN | CloudFront |
| Edge Caching | CloudFront |
| Dedicated Private Connection | Direct Connect |
| Quick Secure Connection | VPN |
| Connect Multiple Networks | Transit Gateway |
| AWS Hardware On-Premises | Outposts |

---

# Chapter 50 — Networking Final Revision Sheet

Know these instantly:

- VPC
- Public Subnet
- Private Subnet
- Route Tables
- Internet Gateway
- NAT Gateway
- Security Groups
- NACL
- Route 53
- CloudFront
- Edge Locations
- Direct Connect
- Site-to-Site VPN
- Transit Gateway
- AWS Outposts

---

# Chapter 51 — Amazon RDS

## Definition

Amazon Relational Database Service (RDS) is a managed relational database service.

---

## Purpose

Run relational databases without managing infrastructure.

---

## Supported Engines

- MySQL
- PostgreSQL
- MariaDB
- Oracle
- Microsoft SQL Server

---

## Benefits

- Automated backups
- Automated patching
- High availability
- Managed service

---

## Use Cases

- Web applications
- Business applications
- ERP systems

---

## Exam Keywords

- Relational Database
- SQL Database
- Managed Database

Answer:

✅ Amazon RDS

---

## Memory Trick

RDS = Relational Database Service

---

# Chapter 52 — Amazon Aurora

## Definition

Amazon Aurora is a high-performance relational database built for the cloud.

---

## Compatibility

- MySQL
- PostgreSQL

---

## Benefits

- Faster performance
- High availability
- Fully managed

---

## Use Cases

- Enterprise applications
- High-performance workloads

---

## Exam Keywords

- Cloud-Native Database
- MySQL Compatible
- PostgreSQL Compatible

Answer:

✅ Aurora

---

## Exam Trap

Question Says:

Enterprise relational database with higher performance

Answer:

✅ Aurora

---

# Chapter 53 — Amazon DynamoDB

## Definition

Fully managed NoSQL database.

---

## Database Type

- Key-Value
- Document Database

---

## Benefits

- Serverless
- Millisecond latency
- Highly scalable

---

## Use Cases

- Mobile applications
- Gaming
- IoT
- Large-scale applications

---

## Exam Keywords

- NoSQL
- Key-Value Database
- Serverless Database

Answer:

✅ DynamoDB

---

## Memory Trick

NoSQL = DynamoDB

---

# Chapter 54 — Amazon Redshift

## Definition

AWS data warehouse service.

---

## Purpose

Analyze large amounts of structured data.

---

## Benefits

- Analytics optimized
- Large-scale reporting
- Business intelligence

---

## Use Cases

- Data warehousing
- Reporting
- Analytics

---

## Exam Keywords

- Data Warehouse
- Analytics Database

Answer:

✅ Redshift

---

## Memory Trick

Redshift = Reports & Analytics

---

# Chapter 55 — Amazon Neptune

## Definition

Managed graph database service.

---

## Purpose

Store and analyze relationships.

---

## Use Cases

- Fraud detection
- Social networks
- Recommendation engines

---

## Benefits

- Relationship analysis
- Graph queries

---

## Exam Keywords

- Graph Database
- Relationship Analysis
- Fraud Detection

Answer:

✅ Neptune

---

## Memory Trick

Neptune Connects Everything

---

# Chapter 56 — Amazon ElastiCache

## Definition

Managed in-memory caching service.

---

## Purpose

Improve application performance.

---

## Benefits

- Reduced database load
- Faster response times
- Improved scalability

---

## Engines

- Redis
- Memcached

---

## Exam Keywords

- Caching
- Performance Improvement

Answer:

✅ ElastiCache

---

## Memory Trick

ElastiCache = Fast Cache

---

# Chapter 57 — Database Services Comparison

| Service | Purpose |
|----------|----------|
| RDS | Relational Database |
| Aurora | High Performance Relational Database |
| DynamoDB | NoSQL Database |
| Redshift | Data Warehouse |
| Neptune | Graph Database |
| ElastiCache | Caching |

---

## Exam Trap

Question Says:

Relational Database

Answer:

✅ RDS

---

Question Says:

NoSQL

Answer:

✅ DynamoDB

---

Question Says:

Data Warehouse

Answer:

✅ Redshift

---

Question Says:

Graph Database

Answer:

✅ Neptune

---

Question Says:

Caching

Answer:

✅ ElastiCache

---

# Chapter 58 — Amazon Athena

## Definition

Serverless query service.

---

## Purpose

Analyze data directly in Amazon S3.

---

## Benefits

- No infrastructure management
- SQL queries
- Pay per query

---

## Use Cases

- Log analysis
- Ad hoc queries
- Data exploration

---

## Exam Keywords

- Query S3 Data
- SQL Queries on S3

Answer:

✅ Athena

---

## Memory Trick

Athena = Ask Questions to S3

---

# Chapter 59 — Amazon EMR

## Definition

Managed big data platform.

---

## Purpose

Process massive datasets.

---

## Technologies

- Hadoop
- Spark
- Hive

---

## Benefits

- Large-scale analytics
- Distributed processing

---

## Exam Keywords

- Hadoop
- Spark
- Big Data

Answer:

✅ Amazon EMR

---

## Memory Trick

EMR = Massive Data Processing

---

# Chapter 60 — Amazon Kinesis

## Definition

Real-time data streaming service.

---

## Purpose

Collect and process streaming data.

---

## Examples

- IoT data
- Clickstream data
- Log streams

---

## Benefits

- Real-time analytics
- Continuous ingestion

---

## Exam Keywords

- Streaming Data
- Real-Time Processing

Answer:

✅ Amazon Kinesis

---

## Memory Trick

Kinesis = Continuous Flow

---

# Chapter 61 — Amazon QuickSight

## Definition

Business Intelligence (BI) service.

---

## Purpose

Create dashboards and reports.

---

## Benefits

- Visualizations
- Charts
- Reporting

---

## Use Cases

- Business analytics
- Executive dashboards

---

## Exam Keywords

- Dashboard
- Charts
- Business Intelligence

Answer:

✅ QuickSight

---

## Memory Trick

QuickSight Helps You See Data

---

# Chapter 62 — Analytics Services Comparison

| Service | Purpose |
|----------|----------|
| Athena | Query S3 Data |
| EMR | Big Data Processing |
| Kinesis | Real-Time Streaming |
| QuickSight | Dashboards & Reports |
| Redshift | Data Warehouse |

---

# Chapter 63 — Amazon Rekognition

## Definition

Image and video analysis service.

---

## Features

- Object detection
- Face analysis
- Scene detection

---

## Use Cases

- Image classification
- Video analysis

---

## Exam Keywords

- Image Analysis
- Video Analysis

Answer:

✅ Rekognition

---

## Memory Trick

Rekognition = Recognize Images

---

# Chapter 64 — Amazon Lex

## Definition

Conversational AI service.

---

## Purpose

Build chatbots and voice bots.

---

## Benefits

- Natural language processing
- Voice interaction

---

## Uses

- Chatbots
- Virtual assistants

---

## Exam Keywords

- Chatbot
- Conversational Interface

Answer:

✅ Amazon Lex

---

## Memory Trick

Lex Powers Alexa

---

# Chapter 65 — Amazon Polly

## Definition

Text-to-speech service.

---

## Purpose

Convert text into spoken audio.

---

## Benefits

- Natural voices
- Multiple languages

---

## Use Cases

- Accessibility
- Voice applications

---

## Exam Keywords

- Text to Speech

Answer:

✅ Amazon Polly

---

## Memory Trick

Polly Talks

---

# Chapter 66 — Amazon Textract

## Definition

Extracts text and data from documents.

---

## Purpose

Process scanned documents automatically.

---

## Benefits

- OCR
- Form extraction
- Table extraction

---

## Exam Keywords

- Extract Text
- Document Processing

Answer:

✅ Textract

---

## Memory Trick

Textract = Text Extract

---

# Chapter 67 — Amazon Comprehend

## Definition

Natural Language Processing (NLP) service.

---

## Purpose

Analyze text.

---

## Features

- Sentiment analysis
- Entity recognition
- Language detection

---

## Use Cases

- Customer feedback analysis
- Document analysis

---

## Exam Keywords

- Sentiment Analysis
- NLP

Answer:

✅ Comprehend

---

## Memory Trick

Comprehend = Understand Text

---

# Chapter 68 — AI Services Comparison

| Service | Purpose |
|----------|----------|
| Rekognition | Image & Video Analysis |
| Lex | Chatbots |
| Polly | Text-to-Speech |
| Textract | Extract Text From Documents |
| Comprehend | NLP & Sentiment Analysis |

---

# Chapter 69 — Most Common Database, Analytics & AI Exam Traps

| Question Says | Answer |
|--------------|---------|
| Relational Database | RDS |
| High Performance Relational DB | Aurora |
| NoSQL | DynamoDB |
| Data Warehouse | Redshift |
| Graph Database | Neptune |
| Caching | ElastiCache |
| Query Data in S3 | Athena |
| Big Data Processing | EMR |
| Streaming Data | Kinesis |
| Dashboards | QuickSight |
| Chatbot | Lex |
| Text-to-Speech | Polly |
| Extract Text | Textract |
| Image Recognition | Rekognition |
| Sentiment Analysis | Comprehend |

---

# Chapter 70 — Database, Analytics & AI Final Revision Sheet

Know these instantly:

- RDS
- Aurora
- DynamoDB
- Redshift
- Neptune
- ElastiCache
- Athena
- EMR
- Kinesis
- QuickSight
- Rekognition
- Lex
- Polly
- Textract
- Comprehend

---
# Domain 3 Handbook — Cloud Technology & Services (CLF-C02)

# Part 5 — Monitoring, Messaging, Migration & Management Services

---

## Purpose

Monitor AWS resources and applications.

---

## What CloudWatch Monitors

- CPU Utilization
- Memory Usage
- Network Activity
- Application Metrics
- Logs

---

## Features

- Metrics
- Dashboards
- Alarms
- Logs

---

## Benefits

- Resource monitoring
- Alerting
- Operational visibility

---

## Exam Keywords

- Monitoring
- Metrics
- Alarms
- Dashboards

Answer:

✅ CloudWatch

---

## Memory Trick

CloudWatch = Watches AWS Resources

---

# Chapter 72 — AWS CloudTrail

## Definition

AWS CloudTrail records API activity inside AWS accounts.

---

## Purpose

Audit and track user activity.

---

## Tracks

- Who performed an action
- What action occurred
- When action occurred

---

## Benefits

- Auditing
- Compliance
- Security investigations

---

## Exam Keywords

- API Logs
- Audit Logs
- User Activity

Answer:

✅ CloudTrail

---

## Memory Trick

CloudTrail Leaves Footprints

---

# Chapter 73 — CloudWatch vs CloudTrail

| Service | Purpose |
|----------|----------|
| CloudWatch | Monitoring |
| CloudTrail | Auditing |

---

## Exam Trap

Question Says:

Metrics

Answer:

✅ CloudWatch

---

Question Says:

API Calls

Answer:

✅ CloudTrail

---

Question Says:

Audit Logs

Answer:

✅ CloudTrail

---

Question Says:

CPU Monitoring

Answer:

✅ CloudWatch

---

# Chapter 74 — Amazon SNS

## Definition

Amazon Simple Notification Service.

---

## Purpose

Send notifications to multiple recipients.

---

## Communication Type

One-to-Many

---

## Delivery Methods

- Email
- SMS
- Lambda
- HTTP
- SQS

---

## Benefits

- Notifications
- Alerts
- Fan-out messaging

---

## Exam Keywords

- Notification Service
- Pub/Sub
- Fan-Out

Answer:

✅ SNS

---

## Memory Trick

SNS = Shout To Everyone

---

# Chapter 75 — Amazon SQS

## Definition

Amazon Simple Queue Service.

---

## Purpose

Decouple applications.

---

## Communication Type

One-to-One

---

## Benefits

- Message buffering
- Decoupling
- Reliability

---

## Use Cases

- Order processing
- Microservices

---

## Exam Keywords

- Queue
- Message Buffer
- Decoupling

Answer:

✅ SQS

---

## Memory Trick

SQS = Wait In Line

---

# Chapter 76 — SNS vs SQS

| Feature | SNS | SQS |
|----------|------|------|
| Communication | One-to-Many | One-to-One |
| Purpose | Notifications | Queuing |
| Delivery | Push | Pull |

---

## Exam Trap

Question Says:

Send notification to many users

Answer:

✅ SNS

---

Question Says:

Queue messages

Answer:

✅ SQS

---

Question Says:

Application decoupling

Answer:

✅ SQS

---

# Chapter 77 — Amazon EventBridge

## Definition

Serverless event bus service.

---

## Purpose

Route events between AWS services.

---

## Benefits

- Event-driven architecture
- Application integration
- Automation

---

## Use Cases

- Trigger Lambda
- Automated workflows

---

## Exam Keywords

- Event Routing
- Event Bus

Answer:

✅ EventBridge

---

## Memory Trick

EventBridge Connects Events

---

# Chapter 78 — AWS Database Migration Service (DMS)

## Definition

Managed database migration service.

---

## Purpose

Move databases into AWS.

---

## Benefits

- Minimal downtime
- Continuous replication
- Heterogeneous migrations

---

## Use Cases

- Oracle to Aurora
- SQL Server to PostgreSQL

---

## Exam Keywords

- Database Migration
- Data Transfer

Answer:

✅ AWS DMS

---

## Memory Trick

DMS = Data Moves Smoothly

---

# Chapter 79 — AWS Schema Conversion Tool (SCT)

## Definition

Converts database schemas to compatible formats.

---

## Purpose

Prepare databases before migration.

---

## Benefits

- Schema conversion
- Migration acceleration

---

## Exam Keywords

- Schema Conversion
- Database Conversion

Answer:

✅ Schema Conversion Tool

---

## Exam Trap

Convert Schema

Answer:

✅ SCT

---

Move Data

Answer:

✅ DMS

---

# Chapter 80 — AWS Migration Hub

## Definition

Central dashboard for tracking migrations.

---

## Purpose

Monitor migration progress.

---

## Benefits

- Central visibility
- Migration tracking

---

## Exam Keywords

- Migration Tracking
- Migration Dashboard

Answer:

✅ Migration Hub

---

## Memory Trick

Migration Hub = Migration Control Center

---

# Chapter 81 — AWS CloudFormation

## Definition

Infrastructure as Code (IaC) service.

---

## Purpose

Provision AWS infrastructure using templates.

---

## Benefits

- Automation
- Consistency
- Repeatability

---

## Features

- Templates
- Stack Creation
- StackSets

---

## Exam Keywords

- Infrastructure as Code
- Templates
- Automated Deployment

Answer:

✅ CloudFormation

---

## Memory Trick

CloudFormation Builds Infrastructure

---

# Chapter 82 — CloudFormation StackSets

## Definition

Deploy infrastructure across multiple AWS accounts and Regions.

---

## Benefits

- Multi-account deployment
- Multi-Region deployment

---

## Exam Keywords

- Multiple Regions
- Infrastructure Replication

Answer:

✅ CloudFormation StackSets

---

# Chapter 83 — AWS Trusted Advisor

## Definition

AWS recommendation engine.

---

## Purpose

Identify best-practice improvements.

---

## Categories

- Cost Optimization
- Security
- Fault Tolerance
- Performance
- Service Limits

---

## Benefits

- Cost savings
- Security improvements
- Resource optimization

---

## Exam Keywords

- Recommendations
- Best Practices

Answer:

✅ Trusted Advisor

---

## Memory Trick

Trusted Advisor = AWS Consultant

---

# Chapter 84 — AWS Systems Manager

## Definition

Operations management service.

---

## Purpose

Manage AWS resources centrally.

---

## Features

- Patch Management
- Automation
- Parameter Store

---

## Benefits

- Centralized management
- Operational efficiency

---

## Exam Keywords

- Operations Management
- Patch Management

Answer:

✅ AWS Systems Manager

---

## Memory Trick

Systems Manager = AWS Control Panel

---

# Chapter 85 — AWS Organizations

## Definition

Service for managing multiple AWS accounts.

---

## Benefits

- Central governance
- Policy management
- Consolidated billing

---

## Features

- Organizational Units
- Service Control Policies

---

## Exam Keywords

- Multiple Accounts
- Central Management

Answer:

✅ AWS Organizations

---

## Memory Trick

Organizations = Manage Many Accounts

---

# Chapter 86 — AWS Organizations Consolidated Billing

## Definition

Single bill for multiple AWS accounts.

---

## Benefits

- Simplified billing
- Shared discounts
- Cost visibility

---

## Exam Keywords

- One Bill
- Multiple Accounts

Answer:

✅ Consolidated Billing

---

## Memory Trick

Many Accounts → One Bill

---

# Chapter 87 — AWS Service Catalog

## Definition

Allows organizations to create approved catalogs of AWS resources.

---

## Benefits

- Governance
- Standardization
- Compliance

---

## Exam Keywords

- Approved Products
- Standardized Resources

Answer:

✅ AWS Service Catalog

---

# Chapter 88 — AWS Control Tower

## Definition

Service that sets up and governs a secure multi-account AWS environment.

---

## Benefits

- Landing zones
- Governance
- Multi-account setup

---

## Exam Keywords

- Multi-Account Governance
- Landing Zone

Answer:

✅ AWS Control Tower

---

## Memory Trick

Control Tower = Airport Control Center

---

# Chapter 89 — Management & Migration Services Comparison

| Service | Purpose |
|----------|----------|
| CloudWatch | Monitoring |
| CloudTrail | Auditing |
| SNS | Notifications |
| SQS | Queueing |
| EventBridge | Event Routing |
| DMS | Database Migration |
| SCT | Schema Conversion |
| Migration Hub | Migration Tracking |
| CloudFormation | Infrastructure as Code |
| Trusted Advisor | Recommendations |
| Systems Manager | Operations Management |
| Organizations | Multi-Account Management |
| Service Catalog | Approved Resource Catalog |
| Control Tower | Multi-Account Governance |

---

# Chapter 90 — Most Common Monitoring & Migration Exam Traps

| Question Says | Answer |
|--------------|---------|
| Monitoring Metrics | CloudWatch |
| API Logs | CloudTrail |
| Audit Logs | CloudTrail |
| Notifications | SNS |
| Queue Messages | SQS |
| Event Routing | EventBridge |
| Database Migration | DMS |
| Schema Conversion | SCT |
| Migration Dashboard | Migration Hub |
| Infrastructure as Code | CloudFormation |
| Multi-Region Deployment | StackSets |
| Best Practice Recommendations | Trusted Advisor |
| Patch Management | Systems Manager |
| Manage Multiple Accounts | Organizations |
| One Bill Across Accounts | Consolidated Billing |
| Landing Zone | Control Tower |

---

# Chapter 91 — Domain 3 Final Revision Sheet

Know these instantly:

- CloudWatch
- CloudTrail
- SNS
- SQS
- EventBridge
- DMS
- Schema Conversion Tool
- Migration Hub
- CloudFormation
- CloudFormation StackSets
- Trusted Advisor
- Systems Manager
- Organizations
- Consolidated Billing
- Service Catalog
- Control Tower

---

# Chapter 92 — Compute Services Mega Comparison

| Service | Purpose | Keywords |
|----------|----------|----------|
| EC2 | Virtual Servers | Compute |
| Lambda | Serverless Compute | Run Code |
| Elastic Beanstalk | Application Deployment | PaaS |
| ECS | Container Management | Docker |
| EKS | Kubernetes Management | Kubernetes |
| Fargate | Serverless Containers | No Servers |
| Lightsail | Simple VPS Hosting | Beginner Friendly |
| Auto Scaling | Automatic Scaling | Elasticity |
| Load Balancer | Traffic Distribution | High Availability |

---

## Compute Exam Traps

| Question Says | Answer |
|--------------|---------|
| Virtual Machine | EC2 |
| Run Code Without Servers | Lambda |
| Docker Containers | ECS |
| Kubernetes | EKS |
| Containers Without Managing Servers | Fargate |
| Beginner Hosting | Lightsail |
| Automatically Add Servers | Auto Scaling |
| Distribute Traffic | Load Balancer |

---

# Chapter 93 — Storage Services Mega Comparison

| Service | Storage Type |
|----------|-------------|
| S3 | Object Storage |
| EBS | Block Storage |
| EFS | File Storage |
| FSx | Specialized File Storage |
| Glacier | Archive Storage |
| Backup | Backup Management |

---

## S3 Storage Classes

| Storage Class | Use Case |
|---------------|----------|
| Standard | Frequently Accessed Data |
| Standard-IA | Rare Access + Immediate Retrieval |
| One Zone-IA | Lower Cost Single AZ |
| Glacier Instant Retrieval | Archive + Instant Access |
| Glacier Flexible Retrieval | Archive |
| Glacier Deep Archive | Lowest Cost Archive |
| Intelligent-Tiering | Automatic Tier Selection |

---

## Storage Exam Traps

| Question Says | Answer |
|--------------|---------|
| Object Storage | S3 |
| EC2 Disk | EBS |
| Shared File Storage | EFS |
| Windows File Share | FSx |
| Backup EBS | Snapshot |
| Archive Data | Glacier |
| Lowest Cost Storage | Deep Archive |
| Rare Access + Instant Retrieval | Standard-IA |

---

# Chapter 94 — Networking Services Mega Comparison

| Service | Purpose |
|----------|----------|
| VPC | Private AWS Network |
| Internet Gateway | Internet Access |
| NAT Gateway | Private Internet Access |
| Route Table | Traffic Routing |
| Security Group | Instance Firewall |
| NACL | Subnet Firewall |
| Route 53 | DNS |
| CloudFront | CDN |
| Direct Connect | Dedicated Connection |
| Site-to-Site VPN | Secure Tunnel |
| Transit Gateway | Network Hub |
| Outposts | AWS On-Premises |

---

## Networking Exam Traps

| Question Says | Answer |
|--------------|---------|
| Private Network | VPC |
| Internet Facing | Public Subnet |
| Database Layer | Private Subnet |
| DNS | Route 53 |
| CDN | CloudFront |
| Dedicated Connection | Direct Connect |
| Fast Setup Secure Connection | VPN |
| Instance Firewall | Security Group |
| Subnet Firewall | NACL |
| Connect Multiple VPCs | Transit Gateway |

---

# Chapter 95 — Database Services Mega Comparison

| Service | Database Type |
|----------|---------------|
| RDS | Relational |
| Aurora | High-Performance Relational |
| DynamoDB | NoSQL |
| Redshift | Data Warehouse |
| Neptune | Graph Database |
| ElastiCache | In-Memory Cache |

---

## Database Exam Traps

| Question Says | Answer |
|--------------|---------|
| SQL Database | RDS |
| MySQL Compatible Cloud DB | Aurora |
| NoSQL | DynamoDB |
| Data Warehouse | Redshift |
| Relationship Analysis | Neptune |
| Fraud Detection | Neptune |
| Caching | ElastiCache |

---

# Chapter 96 — Analytics Services Mega Comparison

| Service | Purpose |
|----------|----------|
| Athena | Query S3 Data |
| EMR | Big Data Processing |
| Kinesis | Streaming Data |
| QuickSight | Dashboards |
| Redshift | Data Warehouse |

---

## Analytics Exam Traps

| Question Says | Answer |
|--------------|---------|
| Query Files in S3 | Athena |
| Hadoop | EMR |
| Spark | EMR |
| Real-Time Streams | Kinesis |
| Dashboards | QuickSight |

---

# Chapter 97 — AI & ML Services Mega Comparison

| Service | Purpose |
|----------|----------|
| Rekognition | Image & Video Analysis |
| Lex | Chatbots |
| Polly | Text-to-Speech |
| Textract | Extract Text |
| Comprehend | NLP |

---

## AI Exam Traps

| Question Says | Answer |
|--------------|---------|
| Image Recognition | Rekognition |
| Video Analysis | Rekognition |
| Chatbot | Lex |
| Voice Assistant | Lex |
| Text to Speech | Polly |
| OCR | Textract |
| Sentiment Analysis | Comprehend |

---

# Chapter 98 — Messaging Services Mega Comparison

| Service | Purpose |
|----------|----------|
| SNS | Notifications |
| SQS | Queueing |
| EventBridge | Event Routing |

---

## Messaging Exam Traps

| Question Says | Answer |
|--------------|---------|
| Send Notification To Many Users | SNS |
| Queue Messages | SQS |
| Application Decoupling | SQS |
| Event Bus | EventBridge |

---

# Chapter 99 — Migration Services Mega Comparison

| Service | Purpose |
|----------|----------|
| DMS | Database Migration |
| SCT | Schema Conversion |
| Migration Hub | Migration Tracking |
| DataSync | File Migration |
| Snowball Edge | Offline Data Migration |
| Snowmobile | Massive Offline Migration |

---

## Migration Exam Traps

| Question Says | Answer |
|--------------|---------|
| Move Database | DMS |
| Convert Schema | SCT |
| Track Migration | Migration Hub |
| Millions of Files | DataSync |
| Petabytes of Data | Snowball Edge |
| Exabytes of Data | Snowmobile |

---

# Chapter 100 — Monitoring & Management Mega Comparison

| Service | Purpose |
|----------|----------|
| CloudWatch | Monitoring |
| CloudTrail | Auditing |
| Trusted Advisor | Recommendations |
| Systems Manager | Operations Management |
| CloudFormation | Infrastructure as Code |
| Organizations | Multi-Account Management |
| Control Tower | Landing Zone Governance |

---

## Monitoring Exam Traps

| Question Says | Answer |
|--------------|---------|
| Metrics | CloudWatch |
| Alarms | CloudWatch |
| Audit Logs | CloudTrail |
| API Activity | CloudTrail |
| Best Practice Recommendations | Trusted Advisor |
| Patch Management | Systems Manager |
| Infrastructure as Code | CloudFormation |
| Multi-Account Governance | Control Tower |

---

# Chapter 101 — Top 100 High-Frequency CLF-C02 Service Keywords

| Keyword | Service |
|----------|----------|
| Virtual Server | EC2 |
| Serverless | Lambda |
| Container | ECS |
| Kubernetes | EKS |
| Serverless Container | Fargate |
| Beginner Hosting | Lightsail |
| Object Storage | S3 |
| Block Storage | EBS |
| Shared Storage | EFS |
| Archive Storage | Glacier |
| DNS | Route 53 |
| CDN | CloudFront |
| Monitoring | CloudWatch |
| Audit Logs | CloudTrail |
| Notifications | SNS |
| Queue | SQS |
| Relational DB | RDS |
| NoSQL | DynamoDB |
| Data Warehouse | Redshift |
| Graph DB | Neptune |
| Cache | ElastiCache |
| Query S3 | Athena |
| Big Data | EMR |
| Streaming | Kinesis |
| Dashboard | QuickSight |
| Image Analysis | Rekognition |
| Chatbot | Lex |
| Text-to-Speech | Polly |
| OCR | Textract |
| NLP | Comprehend |
| Migration | DMS |
| Schema Conversion | SCT |
| Recommendations | Trusted Advisor |
| Infrastructure as Code | CloudFormation |

---

# Chapter 102 — Domain 3 One-Hour Final Revision Sheet

Know these instantly:

## Compute

- EC2
- Lambda
- ECS
- EKS
- Fargate
- Lightsail
- Auto Scaling
- Load Balancer

---

## Storage

- S3
- EBS
- EFS
- FSx
- Glacier
- Snapshot
- Backup

---

## Networking

- VPC
- Route 53
- CloudFront
- Security Group
- NACL
- Direct Connect
- VPN

---

## Databases

- RDS
- Aurora
- DynamoDB
- Redshift
- Neptune
- ElastiCache

---

## Analytics

- Athena
- EMR
- Kinesis
- QuickSight

---

## AI

- Rekognition
- Lex
- Polly
- Textract
- Comprehend

---

## Messaging

- SNS
- SQS
- EventBridge

---

## Migration

- DMS
- SCT
- Migration Hub
- DataSync
- Snowball

---

## Management

- CloudWatch
- CloudTrail
- Trusted Advisor
- Systems Manager
- CloudFormation
- Organizations

---

# Chapter 103 — Domain 3 Final Exam Trap Sheet

| Question Says | Immediate Answer |
|--------------|------------------|
| Virtual Machine | EC2 |
| Run Code | Lambda |
| Docker | ECS |
| Kubernetes | EKS |
| Object Storage | S3 |
| EC2 Disk | EBS |
| Shared Files | EFS |
| Backup EBS | Snapshot |
| DNS | Route 53 |
| CDN | CloudFront |
| Monitoring | CloudWatch |
| Audit Logs | CloudTrail |
| Notifications | SNS |
| Queue | SQS |
| Relational DB | RDS |
| NoSQL | DynamoDB |
| Graph DB | Neptune |
| Data Warehouse | Redshift |
| Caching | ElastiCache |
| Query S3 | Athena |
| Streaming | Kinesis |
| Dashboard | QuickSight |
| Chatbot | Lex |
| OCR | Textract |
| Sentiment Analysis | Comprehend |
| Database Migration | DMS |
| Infrastructure as Code | CloudFormation |

---
