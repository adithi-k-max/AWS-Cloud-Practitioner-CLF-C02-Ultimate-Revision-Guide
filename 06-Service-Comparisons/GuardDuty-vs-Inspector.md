# GuardDuty vs Inspector

One of the most common AWS Cloud Practitioner exam traps is confusing Amazon GuardDuty and Amazon Inspector.

Both are security services.

Both help improve security.

However, they solve completely different problems.

The easiest way to remember them is:

```text
GuardDuty = Detect Threats

Inspector = Find Vulnerabilities
```

---

# Quick Summary

| Service | Primary Purpose |
|----------|----------------|
| GuardDuty | Threat Detection |
| Inspector | Vulnerability Assessment |

---

# Amazon GuardDuty

## Definition

Amazon GuardDuty is a threat detection service.

It continuously monitors AWS accounts and workloads for suspicious or malicious activity.

---

## Purpose

Detect active security threats.

---

## What GuardDuty Looks For

- Suspicious API Calls
- Compromised Credentials
- Unauthorized Access
- Malicious Network Traffic
- Account Takeover Attempts

---

## Common Use Cases

### Security Monitoring

Detect suspicious activity across AWS accounts.

---

### Threat Detection

Identify attacks in real time.

---

### Incident Response

Provide alerts for potential threats.

---

## Exam Keywords

Question Says:

- Threat Detection
- Suspicious Activity
- Malicious Activity
- Unauthorized Access
- Compromised Credentials

Answer:

✅ GuardDuty

---

## Memory Trick

GuardDuty Guards Against Threats

---

# Amazon Inspector

## Definition

Amazon Inspector is a vulnerability assessment service.

It scans AWS resources for security weaknesses.

---

## Purpose

Identify vulnerabilities before attackers exploit them.

---

## What Inspector Looks For

- Missing Security Patches
- Software Vulnerabilities
- Misconfigurations
- Security Weaknesses

---

## Common Use Cases

### Vulnerability Assessment

Identify security issues.

---

### Compliance

Improve security posture.

---

### Risk Reduction

Fix weaknesses before exploitation.

---

## Exam Keywords

Question Says:

- Vulnerability Scan
- Security Assessment
- Missing Patches
- Security Weaknesses

Answer:

✅ Inspector

---

## Memory Trick

Inspector Inspects Vulnerabilities

---

# GuardDuty vs Inspector

| Feature | GuardDuty | Inspector |
|----------|------------|------------|
| Main Purpose | Threat Detection | Vulnerability Assessment |
| Detects Active Threats | Yes | No |
| Finds Security Weaknesses | No | Yes |
| Monitors AWS Activity | Yes | No |
| Checks Missing Patches | No | Yes |
| Detects Suspicious Behavior | Yes | No |

---

# Real-World Example

## Scenario 1

A hacker attempts to access your AWS account using stolen credentials.

Answer:

✅ GuardDuty

Reason:

This is a security threat.

---

## Scenario 2

An EC2 instance is missing critical security patches.

Answer:

✅ Inspector

Reason:

This is a vulnerability.

---

## Scenario 3

Suspicious API calls are detected.

Answer:

✅ GuardDuty

Reason:

Threat detection.

---

## Scenario 4

A security assessment must identify weaknesses.

Answer:

✅ Inspector

Reason:

Vulnerability scanning.

---

# Most Common Exam Traps

## Trap 1

Question Says:

Threat Detection

Answer:

✅ GuardDuty

❌ Inspector

---

## Trap 2

Question Says:

Suspicious Activity

Answer:

✅ GuardDuty

❌ Inspector

---

## Trap 3

Question Says:

Compromised Credentials

Answer:

✅ GuardDuty

❌ Inspector

---

## Trap 4

Question Says:

Vulnerability Assessment

Answer:

✅ Inspector

❌ GuardDuty

---

## Trap 5

Question Says:

Missing Security Patches

Answer:

✅ Inspector

❌ GuardDuty

---

## Trap 6

Question Says:

Security Weaknesses

Answer:

✅ Inspector

❌ GuardDuty

---

# Quick Elimination Table

| Question Contains | Answer |
|-------------------|---------|
| Threat Detection | GuardDuty |
| Suspicious Activity | GuardDuty |
| Malicious Activity | GuardDuty |
| Unauthorized Access | GuardDuty |
| Compromised Credentials | GuardDuty |
| Vulnerability Scan | Inspector |
| Missing Patches | Inspector |
| Security Assessment | Inspector |
| Security Weaknesses | Inspector |

---

# Final Revision

Amazon GuardDuty:

- Threat Detection
- Suspicious Activity
- Compromised Credentials
- Unauthorized Access
- Security Monitoring

---

Amazon Inspector:

- Vulnerability Assessment
- Security Weaknesses
- Missing Patches
- Compliance Checks
- Risk Identification

---

# One-Line Memory Trick

GuardDuty = Detect Bad Activity

Inspector = Find Weak Security
