# DOMAIN 3 — BATCH 02
## Cloud Technology & Services

---

# Question 9 — AWS Compute Optimizer

## Question

Which AWS services or tools can identify rightsizing opportunities for Amazon EC2 instances? (Choose two.)

## Options

| Option | Service |
|----------|----------|
| A | AWS Cost Explorer |
| B | AWS Billing Conductor |
| C | Amazon CodeGuru |
| D | Amazon SageMaker |
| E | AWS Compute Optimizer |

## Correct Answers

✅ AWS Cost Explorer

✅ AWS Compute Optimizer

---

## Why Correct?

### Keywords

- Rightsizing
- EC2 Optimization
- Reduce Cost

### Explanation

AWS Cost Explorer provides cost recommendations.

AWS Compute Optimizer analyzes workloads and recommends better resource sizing.

---

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| B | Billing management only |
| C | Code quality and code recommendations |
| D | Machine learning platform |

---

## Service Deep Dive — AWS Compute Optimizer

### Definition

Analyzes AWS resource utilization and recommends optimal resource sizes.

### Key Features

- EC2 recommendations
- EBS recommendations
- Lambda recommendations
- Cost optimization

### Exam Trap

```text
Rightsizing
=
Compute Optimizer
```

### Memory Trick

Optimizer → Optimize instance size.

### Comparison

| Service | Purpose |
|----------|----------|
| Compute Optimizer | Rightsizing |
| Cost Explorer | Cost Analysis |
| Pricing Calculator | Future Cost Estimates |

---

# Question 12 — AWS Service Catalog

## Question

A company wants to manage deployed IT services and govern its infrastructure as code (IaC) templates.

Which AWS service will meet this requirement?

## Options

| Option | Service |
|----------|----------|
| A | AWS Resource Explorer |
| B | AWS Service Catalog |
| C | AWS Organizations |
| D | AWS Systems Manager |

## Correct Answer

✅ AWS Service Catalog

---

## Why Correct?

### Keywords

- Govern deployments
- Approved templates
- Standardized infrastructure

Service Catalog controls which templates and resources can be deployed.

---

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Resource search service |
| C | Account management |
| D | Operational management |

---

## Service Deep Dive — AWS Service Catalog

### Definition

Allows organizations to govern approved AWS resources and Infrastructure as Code templates.

### Key Features

- Standardized deployments
- Approved products
- Governance controls
- Centralized resource management

### Exam Trap

```text
CloudFormation
=
Creates Infrastructure

Service Catalog
=
Governs Infrastructure
```

### Memory Trick

Catalog = Approved Shopping Catalog

### Comparison

| Service | Purpose |
|----------|----------|
| CloudFormation | Create Infrastructure |
| Service Catalog | Govern Infrastructure |

---

# Question 14 — AWS Glue & Amazon QuickSight

## Question

A company uses a central data platform and wants to discover, transform, and visualize customer data.

Which combination of AWS services should be used? (Choose two.)

## Options

| Option | Service |
|----------|----------|
| A | AWS Glue |
| B | Amazon EFS |
| C | Amazon Redshift |
| D | Amazon QuickSight |
| E | Amazon QLDB |

## Correct Answers

✅ AWS Glue

✅ Amazon QuickSight

---

## Why Correct?

### Keywords

- Discover Data
- Transform Data
- Visualize Data

AWS Glue performs ETL.

Amazon QuickSight creates dashboards and reports.

---

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| B | File Storage |
| C | Data Warehouse |
| E | Ledger Database |

---

## Service Deep Dive — AWS Glue

### Definition

Fully managed Extract, Transform, Load (ETL) service.

### Key Features

- Data discovery
- Data transformation
- Data loading
- Data cataloging

### Exam Trap

```text
ETL
=
AWS Glue
```

### Memory Trick

Glue sticks data together.

---

## Service Deep Dive — Amazon QuickSight

### Definition

Business Intelligence and Data Visualization service.

### Key Features

- Dashboards
- Reports
- Analytics
- Visualization

### Exam Trap

```text
Visualization
=
QuickSight
```

### Memory Trick

QuickSight helps you "see" your data.

### Comparison

| Service | Purpose |
|----------|----------|
| AWS Glue | Transform Data |
| QuickSight | Visualize Data |
| Redshift | Store Analytical Data |

---

# Question 17 — AWS Elastic Beanstalk

## Question

A developer wants to deploy an application quickly on AWS without manually creating the required resources.

## Options

| Option | Service |
|----------|----------|
| A | Amazon EC2 |
| B | AWS Elastic Beanstalk |
| C | AWS CodeBuild |
| D | Amazon Personalize |

## Correct Answer

✅ AWS Elastic Beanstalk

---

## Why Correct?

### Keywords

- Quick Deployment
- No Infrastructure Management

Elastic Beanstalk automatically provisions infrastructure.

---

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Manual setup required |
| C | Build service only |
| D | Recommendation engine |

---

## Service Deep Dive — AWS Elastic Beanstalk

### Definition

Platform-as-a-Service (PaaS) deployment service.

### Key Features

- Upload code
- Automatic provisioning
- Scaling
- Monitoring

### Exam Trap

```text
Quick Application Deployment
=
Elastic Beanstalk
```

### Memory Trick

Upload Code → Beanstalk Handles Infrastructure

### Comparison

| Service | Purpose |
|----------|----------|
| EC2 | Manage Servers |
| Elastic Beanstalk | Deploy Applications |
| Lambda | Run Functions |

---

# Question 18 — Amazon S3 Versioning

## Question

A company stores sensitive customer data in Amazon S3.

The company wants protection against accidental deletion or overwriting.

## Options

| Option | Service |
|----------|----------|
| A | S3 Lifecycle Rules |
| B | S3 Versioning |
| C | S3 Bucket Policies |
| D | S3 Server-Side Encryption |

## Correct Answer

✅ S3 Versioning

---

## Why Correct?

Versioning stores multiple versions of objects.

Deleted or overwritten objects can be restored.

---

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | Lifecycle manages object aging |
| C | Controls access |
| D | Protects confidentiality only |

---

## Service Deep Dive — S3 Versioning

### Definition

Stores multiple versions of an S3 object.

### Key Features

- Recovery from deletion
- Recovery from overwrite
- Data protection

### Exam Trap

```text
Accidental Deletion
≠ Encryption

Accidental Deletion
=
Versioning
```

### Memory Trick

Versioning = Undo Button for S3

---

# Question 19 — AWS CloudFormation

## Question

Which AWS service provides the ability to manage infrastructure as code?

## Options

| Option | Service |
|----------|----------|
| A | AWS CodePipeline |
| B | AWS CodeDeploy |
| C | AWS Direct Connect |
| D | AWS CloudFormation |

## Correct Answer

✅ AWS CloudFormation

---

## Why Correct?

### Keywords

- Infrastructure as Code
- Templates
- Automated Deployment

CloudFormation is AWS's Infrastructure as Code service.

---

## Why Other Options Are Wrong

| Option | Reason |
|----------|----------|
| A | CI/CD workflow |
| B | Application deployment |
| C | Dedicated network connectivity |

---

## Service Deep Dive — AWS CloudFormation

### Definition

Infrastructure as Code service using templates.

### Key Features

- JSON templates
- YAML templates
- Repeatable deployments
- Automation

### Exam Trap

```text
Infrastructure as Code
=
CloudFormation
```

### Memory Trick

Formation = Form Infrastructure Automatically

### Comparison

| Service | Purpose |
|----------|----------|
| CloudFormation | Create Infrastructure |
| Service Catalog | Govern Infrastructure |
| CodeDeploy | Deploy Applications |

---

# Batch 02 Cheat Sheet

## 🔥 Top Services

| Service | Core Concept |
|----------|----------|
| Compute Optimizer | Rightsizing |
| Service Catalog | Governance |
| AWS Glue | ETL |
| QuickSight | Visualization |
| Elastic Beanstalk | PaaS Deployment |
| S3 Versioning | Data Recovery |
| CloudFormation | Infrastructure as Code |

---

## 🔥 Top Facts To Memorize

| Concept | Remember |
|----------|----------|
| Rightsizing | Compute Optimizer |
| Governance of IaC | Service Catalog |
| ETL | AWS Glue |
| Visualization | QuickSight |
| Fast App Deployment | Elastic Beanstalk |
| Recover Deleted S3 Object | Versioning |
| Infrastructure as Code | CloudFormation |

---

## 🔥 Common Exam Traps

| Question Says | Answer |
|----------|----------|
| ETL | Glue |
| Visualization | QuickSight |
| Rightsizing | Compute Optimizer |
| Infrastructure as Code | CloudFormation |
| Govern Templates | Service Catalog |
| Recover Deleted S3 Object | Versioning |
| Deploy App Quickly | Elastic Beanstalk |

---

## 🔥 Most Likely To Reappear

1. CloudFormation vs Service Catalog
2. AWS Glue vs QuickSight
3. Versioning vs Encryption
4. Elastic Beanstalk vs EC2
5. Compute Optimizer vs Cost Explorer

---

# Batch 02 Summary

```text
Compute Optimizer → Rightsizing
Service Catalog   → Governance
AWS Glue          → ETL
QuickSight        → Visualization
Elastic Beanstalk → Fast App Deployment
S3 Versioning     → Recovery from Deletion
CloudFormation    → Infrastructure as Code
```
