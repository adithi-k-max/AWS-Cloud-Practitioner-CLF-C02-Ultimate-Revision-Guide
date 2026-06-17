
# Domain 4 Handbook — Billing, Pricing & Support (CLF-C02)

# Overview

Domain 4 (Billing, Pricing & Support) contributes approximately 12% of the AWS Certified Cloud Practitioner (CLF-C02) exam.

This domain focuses on:

- AWS Pricing Models
- AWS Cost Management Tools
- AWS Billing Concepts
- AWS Support Plans
- AWS Organizations
- Consolidated Billing
- Cost Optimization
- Savings Plans
- Reserved Instances

This is usually the easiest scoring domain because AWS repeatedly asks the same services and concepts.

---

# Chapter 1 — AWS Pricing Philosophy

AWS follows a Pay-As-You-Go pricing model.

Instead of purchasing infrastructure upfront:

Customers pay only for resources consumed.

---

## Benefits

- No upfront investment
- Flexible spending
- Reduced risk
- Cost optimization

---

## Exam Keywords

- Pay only for what you use
- No upfront infrastructure purchase

Answer:

✅ Pay-As-You-Go Pricing

---

# Chapter 2 — AWS Free Tier

## Definition

AWS Free Tier allows customers to explore AWS services at no cost within specified limits.

---

## Types

### Always Free

Services with permanent free usage limits.

---

### 12-Month Free Tier

Available for 12 months after account creation.

---

### Short-Term Trials

Temporary free access.

---

## Benefits

- Learn AWS
- Test services
- Build small projects

---

## Exam Keywords

- Free AWS Usage
- Learn AWS

Answer:

✅ AWS Free Tier

---

# Chapter 3 — AWS Pricing Calculator

## Definition

AWS Pricing Calculator estimates future AWS costs before deployment.

---

## Purpose

Forecast costs for planned architectures.

---

## Benefits

- Cost estimation
- Architecture planning
- Budget forecasting

---

## Exam Keywords

- Estimate Future Costs
- Planned Architecture

Answer:

✅ AWS Pricing Calculator

---

## Memory Trick

Future Cost = Pricing Calculator

---

# Chapter 4 — AWS Cost Explorer

## Definition

AWS Cost Explorer analyzes historical AWS spending and usage.

---

## Purpose

Understand cost trends.

---

## Features

- Historical spending
- Forecasting
- Cost analysis
- Usage reports

---

## Exam Keywords

- Analyze Costs
- Existing Spending

Answer:

✅ AWS Cost Explorer

---

## Memory Trick

Cost Explorer Explores Existing Costs

---

# Chapter 5 — AWS Budgets

## Definition

AWS Budgets monitors costs and usage against defined thresholds.

---

## Purpose

Receive alerts when spending exceeds limits.

---

## Features

- Cost budgets
- Usage budgets
- Forecast alerts
- Notifications

---

## Benefits

- Cost control
- Spending awareness

---

## Exam Keywords

- Budget Alerts
- Cost Threshold

Answer:

✅ AWS Budgets

---

## Memory Trick

Budget = Alert

---

# Chapter 6 — Pricing Calculator vs Cost Explorer vs Budgets

| Service | Purpose |
|----------|----------|
| Pricing Calculator | Estimate Future Cost |
| Cost Explorer | Analyze Existing Cost |
| Budgets | Alert On Cost Thresholds |

---

## Exam Trap

Question Says:

Estimate Monthly Cost

Answer:

✅ Pricing Calculator

---

Question Says:

Analyze Spending

Answer:

✅ Cost Explorer

---

Question Says:

Cost Alerts

Answer:

✅ Budgets

---

# Chapter 7 — AWS Compute Optimizer

## Definition

AWS service that recommends optimal resource configurations.

---

## Purpose

Identify rightsizing opportunities.

---

## Benefits

- Cost savings
- Performance improvements
- Resource optimization

---

## Exam Keywords

- Rightsizing
- Resource Optimization

Answer:

✅ Compute Optimizer

---

## Memory Trick

Compute Optimizer = Right Size Resources

---

# Chapter 8 — AWS Trusted Advisor

## Definition

AWS recommendation service.

---

## Categories

- Cost Optimization
- Security
- Performance
- Fault Tolerance
- Service Limits

---

## Benefits

- Improve architecture
- Reduce cost
- Increase security

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

# Chapter 9 — AWS Organizations

## Definition

AWS Organizations centrally manages multiple AWS accounts.

---

## Benefits

- Central governance
- Policy management
- Billing management

---

## Features

- Organizational Units (OUs)
- Service Control Policies (SCPs)
- Consolidated Billing

---

## Exam Keywords

- Multiple AWS Accounts
- Central Management

Answer:

✅ AWS Organizations

---

## Memory Trick

Organizations = Manage Many Accounts

---

# Chapter 10 — Consolidated Billing

## Definition

Combines billing across multiple AWS accounts.

---

## Benefits

- Single bill
- Simplified accounting
- Shared discounts

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

# Chapter 11 — AWS Support Plans

AWS provides multiple support plans.

---

# Basic Support Plan

## Cost

Free

---

## Features

- Documentation
- Whitepapers
- AWS Personal Health Dashboard
- AWS Trusted Advisor (limited)

---

## Exam Keywords

- Free Support

Answer:

✅ Basic Support

---

# Developer Support Plan

## Purpose

Support for development and testing environments.

---

## Features

- Business-hours support
- Email support

---

## Exam Keywords

- Development Support

Answer:

✅ Developer Support

---

# Business Support Plan

## Purpose

Support for production workloads.

---

## Features

- 24/7 support
- Faster response times
- Full Trusted Advisor

---

## Exam Keywords

- 24/7 Support

Answer:

✅ Business Support

---

# Enterprise On-Ramp Support

## Purpose

Large organizations needing proactive support.

---

## Features

- Faster response
- Guidance

---

## Exam Keywords

- Enterprise-Level Support

Answer:

✅ Enterprise On-Ramp

---

# Enterprise Support Plan

## Purpose

Highest AWS support level.

---

## Features

- Technical Account Manager (TAM)
- Concierge support
- Fastest response times

---

## Exam Keywords

- TAM
- Highest Support

Answer:

✅ Enterprise Support

---

# Chapter 12 — Support Plans Comparison

| Plan | Key Feature |
|--------|------------|
| Basic | Free |
| Developer | Business Hours Support |
| Business | 24/7 Support |
| Enterprise On-Ramp | Enhanced Enterprise Support |
| Enterprise | TAM + Highest Support |

---

## Exam Trap

Question Says:

Free Support

Answer:

✅ Basic

---

Question Says:

24/7 Support

Answer:

✅ Business

---

Question Says:

Technical Account Manager

Answer:

✅ Enterprise

---

# Chapter 13 — AWS Savings Plans

## Definition

Flexible pricing model offering discounts for committed usage.

---

## Commitment

1 Year or 3 Years

---

## Benefits

- Significant discounts
- Flexible usage

---

## Exam Keywords

- Long-Term Savings
- Flexible Commitment

Answer:

✅ Savings Plans

---

## Memory Trick

Savings Plan = Flexible Discount

---

# Chapter 14 — Reserved Instances

## Definition

Discounted EC2 pricing for long-term commitments.

---

## Commitment

- 1 Year
- 3 Years

---

## Benefits

- Lower cost
- Predictable workloads

---

## Exam Keywords

- Predictable Usage
- Commitment

Answer:

✅ Reserved Instances

---

## Memory Trick

Reserved = Predictable Workload

---

# Chapter 15 — Spot Instances

## Definition

Unused AWS capacity available at deep discounts.

---

## Benefits

- Lowest cost
- Up to 90% savings

---

## Limitation

Can be interrupted by AWS.

---

## Use Cases

- Batch processing
- Fault-tolerant workloads

---

## Exam Keywords

- Interruptible
- Cheapest Compute

Answer:

✅ Spot Instances

---

## Memory Trick

Spot = Spare Capacity

---

# Chapter 16 — On-Demand Instances

## Definition

Pay only for compute used without long-term commitment.

---

## Benefits

- Flexibility
- No commitment

---

## Use Cases

- Unpredictable workloads

---

## Exam Keywords

- No Commitment
- Flexible Usage

Answer:

✅ On-Demand

---

# Chapter 17 — Pricing Models Comparison

| Pricing Model | Best Use |
|---------------|----------|
| On-Demand | Unpredictable Workloads |
| Reserved Instances | Predictable Workloads |
| Savings Plans | Flexible Long-Term Savings |
| Spot Instances | Interruptible Workloads |

---

## Exam Trap

Question Says:

No Commitment

Answer:

✅ On-Demand

---

Question Says:

Predictable Workload

Answer:

✅ Reserved Instances

---

Question Says:

Interruptible Workload

Answer:

✅ Spot Instances

---

Question Says:

Flexible Long-Term Discount

Answer:

✅ Savings Plans

---

# Chapter 18 — Cost Optimization Concepts

AWS recommends:

- Rightsizing resources
- Using Reserved Instances
- Using Savings Plans
- Deleting unused resources
- Monitoring costs

---

## Benefits

- Reduced spending
- Better efficiency

---

## Exam Keywords

- Reduce Cost
- Optimize Spending

Answer:

✅ Cost Optimization

---

# Chapter 19 — AWS Billing Dashboard

## Definition

Central location for AWS account billing information.

---

## Features

- Current charges
- Billing reports
- Cost summaries

---

## Benefits

- Cost visibility
- Billing management

---

## Exam Keywords

- Billing Information
- Account Charges

Answer:

✅ AWS Billing Dashboard

---
# Chapter 20 — AWS Marketplace

Definition

AWS Marketplace is a digital catalog where customers can find, test, buy, and deploy third-party software that runs on AWS.

Examples

- Security Tools
- Monitoring Tools
- Databases
- Business Applications

Exam Keywords

Third-party software
Software subscriptions

Answer:

✅ AWS Marketplace

--

# Chapter 21 — AWS Customer Agreement & Pricing Information

Useful AWS Pricing Resources

- AWS Pricing Page
- AWS Pricing Calculator
- Cost Explorer
- AWS Budgets

Purpose

Help customers understand and forecast AWS spending.

--- 

# Chapter 22 — Most Common Domain 4 Exam Traps

| Question Says | Answer |
|--------------|---------|
| Estimate Future Cost | Pricing Calculator |
| Analyze Existing Cost | Cost Explorer |
| Cost Alert | Budgets |
| Rightsizing | Compute Optimizer |
| Recommendations | Trusted Advisor |
| Multiple Accounts | Organizations |
| One Bill | Consolidated Billing |
| Predictable Workload | Reserved Instances |
| Flexible Commitment | Savings Plans |
| Interruptible Workload | Spot Instances |
| No Commitment | On-Demand |
| Free Support | Basic |
| 24/7 Support | Business |
| Technical Account Manager | Enterprise |

---

# Chapter 23 — Domain 4 Master Comparison Table

| Service | Purpose |
|----------|----------|
| Pricing Calculator | Estimate Future Cost |
| Cost Explorer | Analyze Existing Cost |
| Budgets | Cost Alerts |
| Compute Optimizer | Rightsizing |
| Trusted Advisor | Recommendations |
| Organizations | Multi-Account Management |
| Consolidated Billing | Single Bill |
| Savings Plans | Flexible Discounts |
| Reserved Instances | Predictable Workloads |
| Spot Instances | Cheapest Compute |
| Billing Dashboard | Billing Visibility |

---

# Chapter 24 — Domain 4 Final Revision Sheet

Know these instantly:

- AWS Free Tier
- Pricing Calculator
- Cost Explorer
- Budgets
- Compute Optimizer
- Trusted Advisor
- Organizations
- Consolidated Billing
- Basic Support
- Developer Support
- Business Support
- Enterprise On-Ramp
- Enterprise Support
- Savings Plans
- Reserved Instances
- Spot Instances
- On-Demand Instances
- Billing Dashboard

---

# Chapter 25 — Domain 4 One-Hour Revision Sheet

Must Know:

### Cost Tools

- Pricing Calculator
- Cost Explorer
- Budgets
- Compute Optimizer

---

### Pricing Models

- On-Demand
- Reserved
- Spot
- Savings Plans

---

### Organizations

- Organizations
- Consolidated Billing

---

### Support Plans

- Basic
- Developer
- Business
- Enterprise

---

### High Frequency Traps

- Cost Alert → Budgets
- Cost Analysis → Cost Explorer
- Estimate Cost → Pricing Calculator
- Rightsizing → Compute Optimizer
- Predictable Workload → Reserved
- Interruptible Workload → Spot
- Free Support → Basic
- TAM → Enterprise

---
