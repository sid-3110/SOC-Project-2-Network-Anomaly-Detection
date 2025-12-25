## SOC Detection Logic

SOC analysts use logical reasoning to determine whether
network behavior is suspicious.

This section explains how decisions are made.

---

## Key Indicators of Suspicious Activity
- Repeated outbound connections to the same external IP
- Repeated DNS queries to unknown or suspicious domains
- Traffic occurring during non-business hours
- Network activity without user interaction

---

## Context-Based Analysis
SOC analysts always consider context, such as:
- Time of activity
- Frequency of communication
- Known vs unknown destinations
- Baseline behavior of the system

---

## Escalation Criteria
An alert should be escalated when:
- Automated behavior is suspected
- Communication persists over time
- The activity deviates from normal baseline behavior

False positives should be documented and closed properly.
