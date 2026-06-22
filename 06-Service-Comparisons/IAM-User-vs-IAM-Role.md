# IAM User vs IAM Role

One of the most frequently tested AWS Cloud Practitioner concepts is the difference between IAM Users and IAM Roles.

Many students know both are related to permissions but struggle to identify when AWS expects a User and when AWS expects a Role.

The easiest way to remember them is:

```text
IAM User = Person

IAM Role = Temporary Permission
```

---

# Quick Summary

| Feature | IAM User | IAM Role |
|----------|----------|----------|
| Represents | Person/Application | Temporary Identity |
| Long-Term Credentials | Yes | No |
| Username & Password | Yes | No |
| Access Keys | Yes | No |
| Temporary Credentials | No | Yes |
| Common Use | Human Access | Service Access |

---

# IAM User

## Definition

An IAM User is an identity created within AWS for a specific person or application.

Users can sign in directly to AWS and perform actions based on assigned permissions.

---

## Characteristics

- Permanent Identity
- Long-Term Credentials
- Username & Password
- Access Keys

---

## Common Use Cases

### Employee Access

Developers accessing AWS Console.

---

### Administrator Access

AWS Administrators managing resources.

---

### Application Access

Applications using Access Keys.

---

## Exam Keywords

Question Says:

- Employee Access
- Individual Identity
- Long-Term Credentials
- Console Login

Answer:

✅ IAM User

---

## Memory Trick

IAM User = Real Person

---

# IAM Role

## Definition

An IAM Role is an AWS identity that provides temporary permissions.

Roles are assumed when access is needed.

They do not have permanent credentials.

---

## Characteristics

- Temporary Credentials
- Assumed Identity
- No Username
- No Password
- No Access Keys

---

## Common Use Cases

### EC2 Accessing S3

EC2 assumes a role.

---

### Lambda Accessing DynamoDB

Lambda assumes a role.

---

### Cross-Account Access

One AWS account accesses another.

---

### Federated Access

External users access AWS.

---

## Exam Keywords

Question Says:

- Temporary Permissions
- AWS Service Access
- Cross-Account Access
- Assume Role

Answer:

✅ IAM Role

---

## Memory Trick

IAM Role = Borrow Permissions

---

# IAM User vs IAM Role

| Feature | IAM User | IAM Role |
|----------|----------|----------|
| Identity Type | Permanent | Temporary |
| Credentials | Long-Term | Temporary |
| Username | Yes | No |
| Password | Yes | No |
| Access Keys | Yes | No |
| Assume Required | No | Yes |
| Best For | Humans | Services |

---

# Real-World Example

## Scenario 1

A developer needs to log in to AWS every day.

Answer:

✅ IAM User

Reason:

Permanent identity for a person.

---

## Scenario 2

An EC2 instance needs access to an S3 bucket.

Answer:

✅ IAM Role

Reason:

AWS service should assume temporary permissions.

---

## Scenario 3

A Lambda function needs permission to access DynamoDB.

Answer:

✅ IAM Role

Reason:

Temporary permissions for AWS services.

---

## Scenario 4

An administrator requires AWS Console access.

Answer:

✅ IAM User

Reason:

Human user account.

---

# Most Common Exam Traps

## Trap 1

Question Says:

Employee Needs AWS Access

Answer:

✅ IAM User

❌ IAM Role

---

## Trap 2

Question Says:

Developer Login

Answer:

✅ IAM User

❌ IAM Role

---

## Trap 3

Question Says:

EC2 Needs Access To S3

Answer:

✅ IAM Role

❌ IAM User

---

## Trap 4

Question Says:

Lambda Accessing DynamoDB

Answer:

✅ IAM Role

❌ IAM User

---

## Trap 5

Question Says:

Temporary Permissions

Answer:

✅ IAM Role

❌ IAM User

---

## Trap 6

Question Says:

Cross-Account Access

Answer:

✅ IAM Role

❌ IAM User

---

# Quick Elimination Table

| Question Contains | Answer |
|-------------------|---------|
| Employee Access | IAM User |
| Human Identity | IAM User |
| Console Login | IAM User |
| Long-Term Credentials | IAM User |
| Username & Password | IAM User |
| Temporary Permissions | IAM Role |
| Assume Role | IAM Role |
| EC2 Access S3 | IAM Role |
| Lambda Access DynamoDB | IAM Role |
| Cross-Account Access | IAM Role |

---

# Final Revision

IAM User:

- Permanent Identity
- Human User
- Console Login
- Access Keys
- Long-Term Credentials

---

IAM Role:

- Temporary Identity
- Assumed Permissions
- Service Access
- Cross-Account Access
- No Permanent Credentials

---

# One-Line Memory Trick

IAM User = Who You Are

IAM Role = What You Can Temporarily Do
