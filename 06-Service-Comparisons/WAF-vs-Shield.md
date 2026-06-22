# WAF vs Shield

One of the most common AWS Cloud Practitioner security questions involves understanding the difference between AWS WAF and AWS Shield.

Both services help protect applications.

Both improve security.

However, they protect against different threats.

The easiest way to remember them is:

```text
WAF = Protect Web Applications

Shield = Protect Against DDoS Attacks
```

---

# Quick Summary

| Service | Primary Purpose |
|----------|----------------|
| AWS WAF | Web Application Protection |
| AWS Shield | DDoS Protection |

---

# AWS WAF

## Definition

AWS Web Application Firewall (WAF) helps protect web applications from common web exploits and attacks.

It filters and monitors incoming HTTP and HTTPS requests.

---

## Purpose

Protect web applications from malicious web traffic.

---

## Common Threats Blocked

- SQL Injection
- Cross-Site Scripting (XSS)
- Malicious Requests
- Application Layer Attacks

---

## Common Use Cases

### Website Protection

Protect public websites.

---

### API Protection

Protect application APIs.

---

### Traffic Filtering

Allow or block specific requests.

---

## Benefits

- Custom Rules
- Request Filtering
- Application Security

---

## Exam Keywords

Question Says:

- Web Application Firewall
- SQL Injection
- Cross-Site Scripting
- Filter Requests
- HTTP Protection

Answer:

✅ AWS WAF

---

## Memory Trick

WAF = Website Firewall

---

# AWS Shield

## Definition

AWS Shield is a managed DDoS protection service.

It protects AWS applications from Distributed Denial of Service (DDoS) attacks.

---

## Purpose

Protect availability of applications and infrastructure.

---

## Common Threats Blocked

- DDoS Attacks
- Network Flood Attacks
- Infrastructure Attacks

---

## Benefits

- Automatic Protection
- Always On
- Managed DDoS Defense

---

## Shield Standard

Included automatically with AWS services.

Provides protection against common DDoS attacks.

---

## Shield Advanced

Provides:

- Enhanced DDoS Protection
- Detailed Attack Visibility
- Additional Support

---

## Exam Keywords

Question Says:

- DDoS Protection
- Distributed Denial of Service
- Network Attack
- Availability Protection

Answer:

✅ AWS Shield

---

## Memory Trick

Shield = Blocks DDoS Attacks

---

# WAF vs Shield

| Feature | AWS WAF | AWS Shield |
|----------|----------|------------|
| Main Purpose | Web Protection | DDoS Protection |
| Protects Applications | Yes | Yes |
| Filters HTTP Requests | Yes | No |
| Blocks SQL Injection | Yes | No |
| Blocks XSS Attacks | Yes | No |
| Protects Against DDoS | Limited | Yes |
| Protects Availability | No | Yes |

---

# Real-World Example

## Scenario 1

A company wants to block SQL injection attacks.

Answer:

✅ AWS WAF

Reason:

WAF filters malicious web requests.

---

## Scenario 2

A company wants protection against a massive DDoS attack.

Answer:

✅ AWS Shield

Reason:

Shield is designed specifically for DDoS protection.

---

## Scenario 3

A company wants to create rules that block suspicious HTTP requests.

Answer:

✅ AWS WAF

Reason:

WAF provides request filtering.

---

## Scenario 4

A company wants to maintain application availability during large-scale attacks.

Answer:

✅ AWS Shield

Reason:

Shield protects against DDoS attacks.

---

# Most Common Exam Traps

## Trap 1

Question Says:

Web Application Firewall

Answer:

✅ AWS WAF

❌ AWS Shield

---

## Trap 2

Question Says:

SQL Injection

Answer:

✅ AWS WAF

❌ AWS Shield

---

## Trap 3

Question Says:

Cross-Site Scripting

Answer:

✅ AWS WAF

❌ AWS Shield

---

## Trap 4

Question Says:

Filter HTTP Requests

Answer:

✅ AWS WAF

❌ AWS Shield

---

## Trap 5

Question Says:

DDoS Protection

Answer:

✅ AWS Shield

❌ AWS WAF

---

## Trap 6

Question Says:

Distributed Denial of Service

Answer:

✅ AWS Shield

❌ AWS WAF

---

## Trap 7

Question Says:

Protect Availability During Attack

Answer:

✅ AWS Shield

❌ AWS WAF

---

# Quick Elimination Table

| Question Contains | Answer |
|-------------------|---------|
| Web Application Firewall | AWS WAF |
| SQL Injection | AWS WAF |
| Cross-Site Scripting | AWS WAF |
| HTTP Filtering | AWS WAF |
| Web Request Filtering | AWS WAF |
| DDoS Protection | AWS Shield |
| Distributed Denial of Service | AWS Shield |
| Network Flood Attack | AWS Shield |
| Availability Protection | AWS Shield |

---

# Final Revision

AWS WAF:

- Web Application Firewall
- SQL Injection Protection
- XSS Protection
- HTTP Request Filtering
- Application Security

---

AWS Shield:

- DDoS Protection
- Availability Protection
- Managed Security Service
- Shield Standard
- Shield Advanced

---

# One-Line Memory Trick

WAF = Protect The Website

Shield = Protect Against DDoS
