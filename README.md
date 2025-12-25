# SOC Project 2: Suspicious Network Activity Detection

## Objective
The objective of this project is to understand how a SOC Level 1 analyst
detects suspicious network activity by observing DNS queries and outbound
network behavior.

This project focuses on identifying abnormal patterns such as repeated
connections, unusual DNS requests, and beaconing behavior without performing
deep packet analysis or offensive attacks.

---

## What This Project Is About (Simple Explanation)
Every computer on a network communicates with other systems using the internet.
Most of this communication is normal and user-driven.

However, malware often communicates automatically with external servers.
SOC analysts detect this by identifying behavior that does not match
normal human activity.

This project helps build that understanding from a beginner perspective.

---

## Why This Project Matters in SOC
Network-based alerts are very common in SOC environments.
Many security incidents are first detected through abnormal DNS or outbound
connections rather than antivirus alerts.

A SOC Level 1 analyst must be able to:
- Identify suspicious network behavior
- Understand why it is suspicious
- Decide whether escalation is required

---

## Skills Demonstrated
- Understanding of network traffic (SOC level)
- DNS behavior analysis
- Beaconing detection concepts
- Pattern-based investigation
- SOC escalation decision making

---

## Tools & Concepts Used
- DNS logs (conceptual understanding)
- IP reputation awareness
- Network behavior analysis
- SOC investigation mindset

---

## Outcome
This project demonstrates a SOC analyst’s ability to detect suspicious
network behavior by analyzing patterns, repetition, and context rather
than relying on deep technical packet inspection.
