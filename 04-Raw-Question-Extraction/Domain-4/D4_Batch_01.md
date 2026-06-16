# DOMAIN 4 — BATCH 01

## Billing, Pricing & Support

> Domain 4 is the easiest scoring domain in CLF-C02.
>
> AWS repeatedly asks questions about:
>
> * Cost Explorer
> * AWS Budgets
> * Pricing Calculator
> * Trusted Advisor
> * AWS Organizations
> * Consolidated Billing
> * Reserved Instances
> * Spot Instances
> * Savings Plans
> * AWS Support Plans

---

# Question 9 — Rightsizing Opportunities

## Question

Which AWS services or tools can identify rightsizing opportunities for Amazon EC2 instances? (Choose two.)

## Options

| Option | Service               |
| ------ | --------------------- |
| A      | AWS Cost Explorer     |
| B      | AWS Billing Conductor |
| C      | Amazon CodeGuru       |
| D      | Amazon SageMaker      |
| E      | AWS Compute Optimizer |

## Correct Answer

✅ **A. AWS Cost Explorer**

✅ **E. AWS Compute Optimizer**

---

## Why Correct?

Keywords:

* Rightsizing
* Cost reduction
* EC2 optimization

Both services help identify opportunities to reduce costs and optimize EC2 resources.

---

## Why Others Are Wrong?

| Option | Reason                           |
| ------ | -------------------------------- |
| B      | Billing management only          |
| C      | Code reviews and recommendations |
| D      | Machine learning platform        |

---

## Service: AWS Cost Explorer

### Definition

Tool for analyzing AWS costs and usage trends.

### Key Features

* Historical spending analysis
* Cost forecasting
* Usage reports
* Cost trends

### Exam Traps

Analyze Existing Costs = Cost Explorer

Estimate Future Costs = Pricing Calculator

### Memory Trick

Explorer = Explore Spending

---

## Service: AWS Compute Optimizer

### Definition

Service that recommends optimal AWS resource configurations.

### Key Features

* EC2 rightsizing
* Performance recommendations
* Cost optimization

### Exam Traps

Rightsizing = Compute Optimizer

---

# Question 10 — AWS Trusted Advisor

## Question

Which benefits are provided by AWS Trusted Advisor? (Choose two.)

## Options

| Option | Description                      |
| ------ | -------------------------------- |
| A      | Create IAM users                 |
| B      | Deploy EC2 instances             |
| C      | Detect underutilized resources   |
| D      | Improve security recommendations |
| E      | Create VPCs                      |

## Correct Answer

✅ **C. Detect Underutilized Resources**

✅ **D. Improve Security Recommendations**

---

## Why Correct?

Trusted Advisor analyzes:

* Cost optimization
* Security
* Performance
* Fault tolerance
* Service limits

---

## Why Others Are Wrong?

Trusted Advisor provides recommendations only and does not create resources.

---

## Service: AWS Trusted Advisor

### Definition

AWS recommendation engine for best practices.

### Key Features

* Cost optimization
* Security recommendations
* Performance recommendations
* Service limit checks

### Exam Traps

Recommendations = Trusted Advisor

### Memory Trick

Trusted Advisor = AWS Consultant

---

# Question 625 — AWS Budgets

## Question

A company wants to receive alerts when AWS costs exceed a predefined threshold.

## Options

| Option | Service       |
| ------ | ------------- |
| A      | Cost Explorer |
| B      | AWS Budgets   |
| C      | CloudTrail    |
| D      | Route 53      |

## Correct Answer

✅ **B. AWS Budgets**

---

## Why Correct?

AWS Budgets can send alerts when spending exceeds defined thresholds.

---

## Why Others Are Wrong?

| Option | Reason                                           |
| ------ | ------------------------------------------------ |
| A      | Analyzes spending but not primarily for alerting |
| C      | Audit logging                                    |
| D      | DNS service                                      |

---

## Service: AWS Budgets

### Definition

Cost and usage tracking service with alerting capabilities.

### Key Features

* Budget thresholds
* Notifications
* Forecast alerts

### Exam Traps

Alert = Budgets

Analyze = Cost Explorer

### Memory Trick

Budget = Spending Alarm

---

# Question 626 — AWS Pricing Calculator

## Question

A solutions architect wants to estimate the monthly cost of a planned AWS architecture before deployment.

## Options

| Option | Service                |
| ------ | ---------------------- |
| A      | Cost Explorer          |
| B      | AWS Pricing Calculator |
| C      | AWS Budgets            |
| D      | Trusted Advisor        |

## Correct Answer

✅ **B. AWS Pricing Calculator**

---

## Why Correct?

Pricing Calculator estimates future AWS costs before deployment.

---

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| A      | Reviews existing costs |
| C      | Budget monitoring      |
| D      | Recommendations        |

---

## Service: AWS Pricing Calculator

### Definition

Tool used to estimate future AWS architecture costs.

### Key Features

* Cost forecasting
* Architecture planning
* Monthly cost estimates

### Exam Traps

Future Cost = Pricing Calculator

Current Cost = Cost Explorer

### Memory Trick

Calculator = Estimate Before Building

---

# Question 627 — AWS Organizations

## Question

Which AWS service helps manage multiple AWS accounts centrally?

## Options

| Option | Service           |
| ------ | ----------------- |
| A      | AWS Organizations |
| B      | Amazon Cognito    |
| C      | AWS Config        |
| D      | AWS Artifact      |

## Correct Answer

✅ **A. AWS Organizations**

---

## Why Correct?

AWS Organizations provides centralized management for multiple AWS accounts.

---

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| B      | Authentication service |
| C      | Compliance monitoring  |
| D      | Compliance reports     |

---

## Service: AWS Organizations

### Definition

Service for centralized multi-account management.

### Key Features

* Organizational Units (OUs)
* Policy management
* Central governance
* Consolidated billing

### Exam Traps

Multiple Accounts = Organizations

### Memory Trick

Organization = Manage Many Accounts

---

# Question 628 — Consolidated Billing

## Question

What is a benefit of Consolidated Billing in AWS Organizations?

## Options

| Option | Benefit                          |
| ------ | -------------------------------- |
| A      | Faster EC2 performance           |
| B      | Combined billing across accounts |
| C      | Additional Availability Zones    |
| D      | Free support plan                |

## Correct Answer

✅ **B. Combined Billing Across Accounts**

---

## Why Correct?

Consolidated Billing combines charges from multiple AWS accounts into a single bill.

---

## Why Others Are Wrong?

Not related to performance, infrastructure expansion, or support plans.

---

## Concept: Consolidated Billing

### Definition

Single billing statement for multiple AWS accounts.

### Key Features

* Combined usage
* Simpler billing
* Cost visibility

### Memory Trick

Many Accounts → One Bill

---

# Question 629 — Reserved Instances

## Question

Which pricing model provides discounts in exchange for a commitment to consistent usage over 1 or 3 years?

## Options

| Option | Pricing Model      |
| ------ | ------------------ |
| A      | On-Demand          |
| B      | Spot Instances     |
| C      | Reserved Instances |
| D      | Free Tier          |

## Correct Answer

✅ **C. Reserved Instances**

---

## Why Correct?

Reserved Instances provide discounts for long-term predictable workloads.

---

## Why Others Are Wrong?

| Option | Reason                 |
| ------ | ---------------------- |
| A      | No commitment          |
| B      | Interruptible          |
| D      | Promotional usage only |

---

## Service: Reserved Instances

### Definition

Discounted pricing model requiring commitment.

### Key Features

* 1-year or 3-year term
* Significant discounts
* Predictable workloads

### Exam Traps

Predictable Workload = Reserved Instances

### Memory Trick

Reserve = Book in Advance

---

# Question 630 — Spot Instances

## Question

Which AWS pricing model offers the highest discount but can be interrupted by AWS?

## Options

| Option | Pricing Model      |
| ------ | ------------------ |
| A      | Reserved Instances |
| B      | Spot Instances     |
| C      | On-Demand          |
| D      | Dedicated Hosts    |

## Correct Answer

✅ **B. Spot Instances**

---

## Why Correct?

Spot Instances use spare AWS capacity and can be interrupted at any time.

---

## Why Others Are Wrong?

| Option | Reason             |
| ------ | ------------------ |
| A      | Commitment pricing |
| C      | Standard pricing   |
| D      | Dedicated hardware |

---

## Service: Spot Instances

### Definition

Unused AWS capacity offered at steep discounts.

### Key Features

* Very low cost
* Up to 90% discount
* Interruptible workloads

### Exam Traps

Can Tolerate Interruption = Spot

Must Stay Running = Reserved / On-Demand

### Memory Trick

Spot = Spare Capacity

---

# DOMAIN 4 MASTER CHEAT SHEET

## 🔥 Cost Tools Comparison

| Service                | Purpose                |
| ---------------------- | ---------------------- |
| Cost Explorer          | Analyze Existing Costs |
| AWS Budgets            | Cost Alerts            |
| AWS Pricing Calculator | Estimate Future Costs  |
| Compute Optimizer      | Rightsizing            |
| Trusted Advisor        | Recommendations        |

---

## 🔥 Pricing Models

| Model         | Best Use                   |
| ------------- | -------------------------- |
| On-Demand     | Unpredictable Workloads    |
| Reserved      | Predictable Workloads      |
| Spot          | Interruptible Workloads    |
| Savings Plans | Flexible Long-Term Savings |

---

## 🔥 AWS Support Plans

| Plan       | Key Feature            |
| ---------- | ---------------------- |
| Basic      | Free                   |
| Developer  | Business-Hours Support |
| Business   | 24/7 Support           |
| Enterprise | Highest Support Level  |

---

## 🔥 Top 15 Facts To Memorize

1. Cost Analysis = Cost Explorer
2. Cost Alerts = AWS Budgets
3. Future Estimates = Pricing Calculator
4. Recommendations = Trusted Advisor
5. Rightsizing = Compute Optimizer
6. Multi-Account Management = Organizations
7. One Bill = Consolidated Billing
8. Predictable Workload = Reserved Instances
9. Interruptible Workload = Spot Instances
10. Free Plan = Basic Support
11. 24/7 Support = Business Plan
12. Highest Support = Enterprise Support
13. Cost Forecasting = Cost Explorer
14. Budget Threshold Alerts = AWS Budgets
15. Savings Plans Reduce Long-Term Costs

---

# Final Domain 4 Revision

```text
Cost Explorer      → Analyze Existing Costs
AWS Budgets        → Cost Alerts
Pricing Calculator → Future Cost Estimates
Trusted Advisor    → Recommendations
Compute Optimizer  → Rightsizing
Organizations      → Multi-Account Management
Consolidated Bill  → One Bill For Many Accounts
Reserved           → Predictable Workload
Spot               → Interruptible Workload
Savings Plans      → Flexible Long-Term Savings
Basic Support      → Free
Business Support   → 24/7 Support
Enterprise Support → Highest Support Level
```

---

# 🎯 CLF-C02 STATUS

✅ Domain 1 — Complete

✅ Domain 2 — Complete

✅ Domain 4 — Complete

🟡 Domain 3 — Complete (Major recurring services covered)

For last-minute revision:

1. Read Domain 2 Master Cheat Sheet
2. Read Domain 4 Master Cheat Sheet
3. Review Domain 3 Service Comparisons
4. Sleep well before the exam

These domains cover the overwhelming majority of recurring AWS CLF-C02 concepts and exam traps.
