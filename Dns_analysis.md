## DNS Analysis 

DNS (Domain Name System) is used to translate domain names into IP addresses.
For example, when a user visits a website, the system first makes a DNS request.

Because DNS is required for almost all internet activity and is usually allowed
through firewalls, attackers often abuse DNS for malicious communication.

---

## Normal DNS Behavior
Normal DNS behavior includes:
- Queries to popular or known domains
- Requests that occur when a user is browsing
- DNS activity that stops when browsing ends

This type of behavior is considered low risk.

---

## Suspicious DNS Behavior
Suspicious DNS behavior may include:
- Queries to random or meaningless domain names
- Very long or unusual domain structures
- Repeated DNS queries at regular intervals
- DNS activity without visible user interaction

Such behavior may indicate malware attempting to communicate
with a command-and-control server.

SOC analysts investigate these patterns rather than individual DNS queries.
