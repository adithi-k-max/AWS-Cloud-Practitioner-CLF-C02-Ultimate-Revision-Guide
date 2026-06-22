# EBS vs EFS vs S3

One of the most frequently tested AWS Cloud Practitioner topics is storage.

Many students confuse:

- Amazon EBS
- Amazon EFS
- Amazon S3

The easiest way to remember them is:

```text
S3  = Object Storage

EBS = Block Storage

EFS = File Storage
```

---

# Quick Summary

| Service | Storage Type |
|----------|-------------|
| S3 | Object Storage |
| EBS | Block Storage |
| EFS | File Storage |

---

# Amazon S3

## Definition

Amazon S3 (Simple Storage Service) is AWS object storage service.

Data is stored as objects inside buckets.

---

## Characteristics

- Object Storage
- Highly Scalable
- Highly Durable
- Fully Managed

---

## Common Use Cases

### Website Assets

Store:

- Images
- Videos
- CSS Files
- JavaScript Files

---

### Backups

Store backup files.

---

### Data Lakes

Store large datasets.

---

### Static Website Hosting

Host static websites directly from S3.

---

## Exam Keywords

Question Says:

- Object Storage
- Store Files
- Unlimited Storage
- Website Assets
- Backup Storage

Answer:

✅ Amazon S3

---

## Memory Trick

S3 = Store Anything

---

# Amazon EBS

## Definition

Amazon Elastic Block Store (EBS) provides block storage for EC2 instances.

Think of it as a virtual hard disk attached to a server.

---

## Characteristics

- Block Storage
- Attached To EC2
- Persistent Storage
- High Performance

---

## Common Use Cases

### Operating Systems

Store Linux and Windows operating systems.

---

### Databases

Store database files.

---

### Enterprise Applications

Store application data.

---

## Exam Keywords

Question Says:

- Block Storage
- EC2 Storage
- Hard Drive
- Attached Storage

Answer:

✅ Amazon EBS

---

## Memory Trick

EBS = Hard Drive For EC2

---

# Amazon EFS

## Definition

Amazon Elastic File System (EFS) provides shared file storage.

Multiple EC2 instances can access the same file system simultaneously.

---

## Characteristics

- File Storage
- Shared Access
- Multiple EC2 Instances
- Automatic Scaling

---

## Common Use Cases

### Shared Web Servers

Multiple servers access the same files.

---

### Content Management Systems

Shared storage for applications.

---

### Enterprise Applications

Shared file repositories.

---

## Exam Keywords

Question Says:

- Shared Storage
- File Storage
- Multiple EC2 Instances

Answer:

✅ Amazon EFS

---

## Memory Trick

EFS = Shared Folder

---

# EBS vs EFS vs S3

| Feature | EBS | EFS | S3 |
|----------|-----|-----|-----|
| Storage Type | Block | File | Object |
| Attached To EC2 | Yes | Yes | No |
| Shared By Multiple EC2 | No | Yes | N/A |
| Unlimited Scale | No | Yes | Yes |
| Common Use Case | OS & Databases | Shared Files | General Storage |

---

# Real-World Example

## Scenario 1

You need storage for an EC2 operating system.

Answer:

✅ EBS

Reason:

Block storage attached to EC2.

---

## Scenario 2

Ten EC2 instances must access the same files.

Answer:

✅ EFS

Reason:

Shared file storage.

---

## Scenario 3

Store millions of images and videos.

Answer:

✅ S3

Reason:

Object storage with virtually unlimited scalability.

---

# Most Common Exam Traps

## Trap 1

Question Says:

Object Storage

Answer:

✅ S3

❌ EBS

❌ EFS

---

## Trap 2

Question Says:

Block Storage

Answer:

✅ EBS

❌ EFS

❌ S3

---

## Trap 3

Question Says:

File Storage

Answer:

✅ EFS

❌ EBS

❌ S3

---

## Trap 4

Question Says:

Shared Storage For Multiple EC2 Instances

Answer:

✅ EFS

---

## Trap 5

Question Says:

Hard Drive For EC2

Answer:

✅ EBS

---

## Trap 6

Question Says:

Store Images And Videos

Answer:

✅ S3

---

## Trap 7

Question Says:

Unlimited Object Storage

Answer:

✅ S3

---

# Quick Elimination Table

| Question Contains | Answer |
|-------------------|---------|
| Object Storage | S3 |
| Bucket | S3 |
| Website Assets | S3 |
| Images & Videos | S3 |
| Block Storage | EBS |
| EC2 Hard Drive | EBS |
| Operating System | EBS |
| Database Storage | EBS |
| File Storage | EFS |
| Shared Storage | EFS |
| Multiple EC2 Access | EFS |

---

# Final Revision

Amazon S3:

- Object Storage
- Buckets
- Images
- Videos
- Backups
- Static Websites

---

Amazon EBS:

- Block Storage
- Attached To EC2
- Operating Systems
- Databases
- Persistent Storage

---

Amazon EFS:

- File Storage
- Shared Access
- Multiple EC2 Instances
- Automatic Scaling

---

# One-Line Memory Trick

S3 = Store Objects

EBS = EC2 Hard Drive

EFS = Shared Folder
