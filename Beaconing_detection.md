## Beaconing Detection 

Beaconing refers to automated and periodic communication between
an infected system and an external server controlled by an attacker.

Unlike human behavior, beaconing occurs on a predictable schedule.

---

## Beaconing Characteristics
Typical beaconing behavior includes:
- Communication with the same external IP or domain
- Fixed time intervals (for example, every 60 seconds)
- No direct user activity triggering the communication

---

## Why Beaconing Is Important in SOC
Beaconing often indicates:
- Malware presence
- Command-and-control communication
- Persistence mechanisms

SOC analysts detect beaconing by identifying repetition,
regular timing, and lack of user involvement.

Humans behave randomly. Malware behaves predictably.
