# AWS Shared Responsibility Model

The Shared Responsibility Model is one of the most frequently tested concepts in the AWS Certified Cloud Practitioner (CLF-C02) exam.

Many questions directly test whether AWS or the customer is responsible for a specific task.

---

# Core Concept

AWS is responsible for:

Security OF The Cloud

Customers are responsible for:

Security IN The Cloud

---

# AWS Responsibilities

AWS manages:

- Physical Servers
- Storage Hardware
- Networking Hardware
- Data Centers
- Power
- Cooling
- Physical Security

---

# Customer Responsibilities

Customers manage:

- IAM Permissions
- User Accounts
- Customer Data
- Security Groups
- Operating Systems on EC2
- Application Security
- Encryption Configuration

---

# Quick Comparison

| Responsibility | AWS | Customer |
|---------------|-----|----------|
| Data Centers | ✅ | ❌ |
| Physical Hardware | ✅ | ❌ |
| Power & Cooling | ✅ | ❌ |
| Network Infrastructure | ✅ | ❌ |
| IAM Permissions | ❌ | ✅ |
| Customer Data | ❌ | ✅ |
| Security Groups | ❌ | ✅ |
| EC2 Operating System | ❌ | ✅ |

---

# Most Common Exam Traps

Question Says:

Physical Security

Answer:

✅ AWS

---

Question Says:

Data Center Maintenance

Answer:

✅ AWS

---

Question Says:

Cooling Systems

Answer:

✅ AWS

---

Question Says:

IAM Permissions

Answer:

✅ Customer

---

Question Says:

Customer Data

Answer:

✅ Customer

---

Question Says:

Security Groups

Answer:

✅ Customer

---

Question Says:

Operating System On EC2

Answer:

✅ Customer

---

# One-Line Memory Trick

AWS Secures The Cloud

Customers Secure Their Workloads
