# CloudTrail vs CloudWatch

One of the most common AWS Cloud Practitioner exam traps is confusing CloudTrail and CloudWatch.

Both are monitoring-related services, but they solve completely different problems.

---

# Quick Summary

| Service | Primary Purpose |
|----------|----------------|
| CloudTrail | Audit AWS Account Activity |
| CloudWatch | Monitor AWS Resources |

---

# Amazon CloudTrail

## Definition

AWS CloudTrail records actions performed inside an AWS account.

It captures API calls and account activity.

CloudTrail helps answer:

- Who performed an action?
- When was the action performed?
- What resource was affected?
- Which API call was used?

---

## Common Use Cases

### Security Investigations

Example:

Who deleted an S3 bucket?

CloudTrail can identify:

- User
- Time
- Action

---

### Compliance Audits

Organizations can track:

- User activities
- Resource modifications
- Administrative actions

---

### Governance

Maintain historical records of account activity.

---

## What CloudTrail Records

Examples:

- EC2 Instance Created
- S3 Bucket Deleted
- IAM Policy Modified
- Security Group Changed
- User Login Events

---

## Exam Keywords

Question Says:

- API Calls
- Audit Logs
- User Activity
- Account Activity
- Governance
- Compliance Auditing

Answer:

✅ CloudTrail

---

## Memory Trick

CloudTrail leaves footprints.

Just like a trail behind someone walking.

CloudTrail tracks what happened.

---

# Amazon CloudWatch

## Definition

Amazon CloudWatch monitors AWS resources and applications.

It collects metrics, logs, and events.

CloudWatch helps answer:

- Is the resource healthy?
- Is CPU utilization high?
- Is memory usage increasing?
- Is the application performing correctly?

---

## Common Use Cases

### Resource Monitoring

Monitor:

- EC2 CPU Utilization
- Network Traffic
- Disk Activity

---

### Application Monitoring

Track:

- Errors
- Performance
- Logs

---

### Alarms

Trigger notifications when thresholds are exceeded.

Example:

CPU Usage > 80%

↓

Send Notification

---

## What CloudWatch Monitors

Examples:

- CPU Usage
- Memory Usage
- Network Traffic
- Application Logs
- Performance Metrics

---

## Exam Keywords

Question Says:

- Monitoring
- Metrics
- Resource Health
- Performance Monitoring
- Alarms

Answer:

✅ CloudWatch

---

## Memory Trick

CloudWatch watches resources.

It tells you how resources are performing.

---

# CloudTrail vs CloudWatch

| Feature | CloudTrail | CloudWatch |
|----------|------------|------------|
| Primary Purpose | Auditing | Monitoring |
| Tracks User Activity | Yes | No |
| Tracks API Calls | Yes | No |
| Tracks Resource Performance | No | Yes |
| Provides Metrics | No | Yes |
| Provides Alarms | No | Yes |
| Used For Compliance | Yes | No |
| Used For Resource Health | No | Yes |

---

# Real-World Example

Imagine an EC2 instance suddenly stops working.

Question 1:

Is CPU utilization too high?

Answer:

✅ CloudWatch

Reason:

CloudWatch monitors resource performance.

---

Question 2:

Who terminated the EC2 instance?

Answer:

✅ CloudTrail

Reason:

CloudTrail records account activity and API calls.

---

# Most Common Exam Traps

## Trap 1

Question Says:

Monitor CPU utilization.

Answer:

✅ CloudWatch

❌ CloudTrail

---

## Trap 2

Question Says:

Track API calls.

Answer:

✅ CloudTrail

❌ CloudWatch

---

## Trap 3

Question Says:

Create an alarm when memory usage exceeds a threshold.

Answer:

✅ CloudWatch

❌ CloudTrail

---

## Trap 4

Question Says:

Determine who deleted an S3 bucket.

Answer:

✅ CloudTrail

❌ CloudWatch

---

## Trap 5

Question Says:

Compliance auditing.

Answer:

✅ CloudTrail

❌ CloudWatch

---

# Quick Elimination Table

| Question Contains | Answer |
|-------------------|---------|
| API Calls | CloudTrail |
| Audit Logs | CloudTrail |
| User Activity | CloudTrail |
| Compliance | CloudTrail |
| Governance | CloudTrail |
| Monitoring | CloudWatch |
| Metrics | CloudWatch |
| Resource Health | CloudWatch |
| Alarms | CloudWatch |
| CPU Utilization | CloudWatch |

---

# Final Revision

CloudTrail:

- Audit Service
- API Calls
- User Activity
- Compliance
- Governance
- Security Investigations

---

CloudWatch:

- Monitoring Service
- Metrics
- Logs
- Alarms
- Resource Performance
- Resource Health

---

# One-Line Memory Trick

CloudTrail = Who Did It?

CloudWatch = How Is It Performing?
