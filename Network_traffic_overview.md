## Network Traffic Overview 

Network traffic refers to the communication between computers, servers,
and applications over a network.

In a SOC environment, analysts do not inspect every packet.
Instead, they observe traffic patterns to determine whether the behavior
is normal or suspicious.

---

## Normal Network Traffic (Human Behavior)
Normal network traffic usually has the following characteristics:
- Triggered by user actions (opening a browser, clicking a link)
- Communication with well-known domains
- Irregular timing
- Stops when the user closes the application

Example:
A user opens a website, the system makes a few DNS requests,
and traffic stops once browsing ends.

---

## Suspicious Network Traffic (Automated Behavior)
Suspicious network traffic often shows:
- Repeated communication without user action
- Connections to unknown or random domains
- Fixed time intervals (very regular)
- Activity during unusual hours

SOC analysts focus on identifying automated behavior
because malware does not behave like humans.
