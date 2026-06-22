# SNS vs SQS

One of the most common AWS Cloud Practitioner exam traps is confusing Amazon SNS and Amazon SQS.

Both are messaging services.

Both help applications communicate.

However, they solve different problems.

The easiest way to remember them is:

```text
SNS = Send Notifications

SQS = Store Messages In A Queue
```

---

# Quick Summary

| Service | Primary Purpose |
|----------|----------------|
| SNS | Notifications |
| SQS | Message Queue |

---

# Amazon Simple Notification Service (SNS)

## Definition

Amazon SNS is a fully managed publish/subscribe messaging service.

It sends messages to multiple subscribers simultaneously.

---

## Messaging Model

One-To-Many

---

## Characteristics

- Push-Based Service
- Fan-Out Messaging
- Multiple Subscribers
- Real-Time Notifications

---

## Common Use Cases

### Email Notifications

Send messages to many users.

---

### SMS Alerts

Send text message notifications.

---

### Application Alerts

Notify administrators.

---

### Fan-Out Architecture

One message delivered to multiple recipients.

---

## Exam Keywords

Question Says:

- Notifications
- Publish/Subscribe
- Fan-Out
- One-To-Many
- Push Messaging

Answer:

✅ SNS

---

## Memory Trick

SNS = Shout Notification Service

One message reaches many people.

---

# Amazon Simple Queue Service (SQS)

## Definition

Amazon SQS is a fully managed message queue service.

It stores messages until they are processed.

---

## Messaging Model

One-To-One

---

## Characteristics

- Pull-Based Service
- Message Queue
- Decouples Applications
- Reliable Delivery

---

## Common Use Cases

### Background Processing

Store tasks for later execution.

---

### Application Decoupling

Separate application components.

---

### Order Processing

Queue customer requests.

---

### Workload Buffering

Handle traffic spikes.

---

## Exam Keywords

Question Says:

- Queue Messages
- Decouple Applications
- Reliable Messaging
- One-To-One
- Message Buffer

Answer:

✅ SQS

---

## Memory Trick

SQS = Stand In Queue

Messages wait until processed.

---

# SNS vs SQS

| Feature | SNS | SQS |
|----------|-----|-----|
| Primary Purpose | Notifications | Queue Messages |
| Messaging Type | One-To-Many | One-To-One |
| Communication Model | Push | Pull |
| Multiple Subscribers | Yes | No |
| Message Storage | No | Yes |
| Decouple Applications | No | Yes |
| Fan-Out Messaging | Yes | No |

---

# Real-World Example

## Scenario 1

A company wants to send a security alert to thousands of users.

Answer:

✅ SNS

Reason:

One notification sent to many recipients.

---

## Scenario 2

An application receives customer orders that must be processed one by one.

Answer:

✅ SQS

Reason:

Queue-based processing.

---

## Scenario 3

A company wants to notify:

- Email Users
- SMS Users
- Applications

Using one message.

Answer:

✅ SNS

Reason:

Publish once, deliver to many subscribers.

---

## Scenario 4

A company wants to separate frontend and backend processing.

Answer:

✅ SQS

Reason:

Decouples application components.

---

# Most Common Exam Traps

## Trap 1

Question Says:

Notifications

Answer:

✅ SNS

❌ SQS

---

## Trap 2

Question Says:

Publish/Subscribe

Answer:

✅ SNS

❌ SQS

---

## Trap 3

Question Says:

Fan-Out

Answer:

✅ SNS

❌ SQS

---

## Trap 4

Question Says:

Queue Messages

Answer:

✅ SQS

❌ SNS

---

## Trap 5

Question Says:

Decouple Applications

Answer:

✅ SQS

❌ SNS

---

## Trap 6

Question Says:

Store Messages Until Processed

Answer:

✅ SQS

❌ SNS

---

## Trap 7

Question Says:

One Message To Multiple Receivers

Answer:

✅ SNS

❌ SQS

---

# Quick Elimination Table

| Question Contains | Answer |
|-------------------|---------|
| Notifications | SNS |
| Publish/Subscribe | SNS |
| Fan-Out | SNS |
| Push Messaging | SNS |
| One-To-Many | SNS |
| Queue Messages | SQS |
| Message Buffer | SQS |
| Decoupling | SQS |
| Reliable Queue | SQS |
| One-To-One | SQS |

---

# Final Revision

Amazon SNS:

- Notifications
- Publish/Subscribe
- One-To-Many
- Push Model
- Fan-Out Messaging

---

Amazon SQS:

- Message Queue
- One-To-One
- Pull Model
- Decoupling
- Reliable Message Storage

---

# One-Line Memory Trick

SNS = Send Notifications

SQS = Store Queued Messages
