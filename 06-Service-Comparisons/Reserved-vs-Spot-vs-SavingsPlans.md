# Reserved Instances vs Spot Instances vs Savings Plans

One of the most common AWS Cloud Practitioner exam topics is AWS pricing models.

Many students confuse:

- Reserved Instances (RI)
- Spot Instances
- Savings Plans

The key is understanding the trade-off between:

- Cost
- Flexibility
- Commitment

---

# Quick Summary

| Pricing Model | Best For |
|--------------|----------|
| Reserved Instances | Predictable Workloads |
| Spot Instances | Flexible Workloads |
| Savings Plans | Flexible Long-Term Savings |

---

# Reserved Instances (RI)

## Definition

Reserved Instances provide discounted pricing in exchange for a commitment to use AWS resources for a fixed period.

---

## Commitment Period

- 1 Year
- 3 Years

---

## Benefits

- Significant cost savings
- Predictable billing
- Suitable for long-term workloads

---

## Best Use Cases

### Production Applications

Applications running continuously.

---

### Databases

Long-running database workloads.

---

### Enterprise Systems

Predictable infrastructure requirements.

---

## Exam Keywords

Question Says:

- Predictable Workload
- Long-Term Commitment
- Consistent Usage
- Lower Cost Than On-Demand

Answer:

✅ Reserved Instances

---

## Memory Trick

Reserved = Reserve Capacity

---

# Spot Instances

## Definition

Spot Instances use AWS spare capacity at heavily discounted prices.

AWS can reclaim the instance at any time.

---

## Characteristics

- Lowest Cost
- Interruptible
- No Availability Guarantee

---

## Benefits

- Huge Discounts
- Cost Optimization

---

## Best Use Cases

### Batch Processing

Workloads that can restart.

---

### Testing Environments

Temporary environments.

---

### Big Data Jobs

Fault-tolerant processing.

---

## Exam Keywords

Question Says:

- Interruptible Workload
- Spare Capacity
- Lowest Cost
- Flexible Workload

Answer:

✅ Spot Instances

---

## Memory Trick

Spot = Cheap But Can Disappear

---

# Savings Plans

## Definition

Savings Plans provide discounted pricing in exchange for a commitment to a consistent amount of usage.

Unlike Reserved Instances, Savings Plans offer more flexibility.

---

## Commitment Period

- 1 Year
- 3 Years

---

## Benefits

- Cost Savings
- Greater Flexibility
- Broad Service Coverage

---

## Best Use Cases

### Long-Term AWS Usage

Customers committed to AWS.

---

### Evolving Architectures

Applications expected to change over time.

---

### Flexible Workloads

Workloads requiring pricing flexibility.

---

## Exam Keywords

Question Says:

- Flexible Savings
- Long-Term Discount
- Usage Commitment

Answer:

✅ Savings Plans

---

## Memory Trick

Savings Plans = Flexible Reserved Pricing

---

# Reserved Instances vs Spot Instances vs Savings Plans

| Feature | Reserved Instances | Spot Instances | Savings Plans |
|----------|------------------|----------------|---------------|
| Cost Savings | High | Highest | High |
| Commitment Required | Yes | No | Yes |
| Interruptible | No | Yes | No |
| Flexibility | Low | High | High |
| Best For | Predictable Workloads | Flexible Workloads | Long-Term Flexible Workloads |

---

# Real-World Example

## Scenario 1

A company runs a database 24/7 for several years.

Answer:

✅ Reserved Instances

Reason:

Predictable workload.

---

## Scenario 2

A company processes large batches of data overnight.

Answer:

✅ Spot Instances

Reason:

Workload can tolerate interruptions.

---

## Scenario 3

A company wants discounts but expects infrastructure changes.

Answer:

✅ Savings Plans

Reason:

Provides flexibility with savings.

---

# Most Common Exam Traps

## Trap 1

Question Says:

Predictable Usage

Answer:

✅ Reserved Instances

❌ Spot Instances

❌ Savings Plans

---

## Trap 2

Question Says:

Lowest Cost

Answer:

✅ Spot Instances

❌ Reserved Instances

❌ Savings Plans

---

## Trap 3

Question Says:

Can Be Interrupted

Answer:

✅ Spot Instances

❌ Reserved Instances

❌ Savings Plans

---

## Trap 4

Question Says:

Flexible Savings

Answer:

✅ Savings Plans

❌ Reserved Instances

❌ Spot Instances

---

## Trap 5

Question Says:

Long-Term Commitment

Answer:

✅ Reserved Instances

or

✅ Savings Plans

(Read carefully for flexibility requirements.)

---

## Trap 6

Question Says:

Spare AWS Capacity

Answer:

✅ Spot Instances

---

# Quick Elimination Table

| Question Contains | Answer |
|-------------------|---------|
| Predictable Workload | Reserved Instances |
| Long-Term Commitment | Reserved Instances |
| Reserved Capacity | Reserved Instances |
| Lowest Cost | Spot Instances |
| Spare Capacity | Spot Instances |
| Interruptible Workload | Spot Instances |
| Flexible Savings | Savings Plans |
| Flexible Long-Term Discount | Savings Plans |
| Usage Commitment | Savings Plans |

---

# Final Revision

Reserved Instances:

- Predictable Workloads
- 1-Year Commitment
- 3-Year Commitment
- Cost Savings
- Long-Term Usage

---

Spot Instances:

- Lowest Cost
- Spare Capacity
- Interruptible
- Flexible Workloads
- Batch Jobs

---

Savings Plans:

- Flexible Savings
- Long-Term Discount
- Usage Commitment
- Greater Flexibility
- Cost Optimization

---

# One-Line Memory Trick

Reserved Instances = Predictable

Spot Instances = Cheapest

Savings Plans = Flexible Savings
