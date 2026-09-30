---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-298"
status: "Stable"
---
# CAPEC-298: UDP Ping

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An adversary sends a UDP datagram to the remote host to determine if the host is alive. If a UDP datagram is sent to an open UDP port there is very often no response, so a typical strategy for using a UDP ping is to send the datagram to a random high port on the target. The goal is to solicit an 'ICMP port unreachable' message from the target, indicating that the host is alive. UDP pings are useful because some firewalls are not configured to block UDP datagrams sent to strange or typically unused ports, like ports in the 65K range. Additionally, while some firewalls may filter incoming ICMP, weaknesses in firewall rule-sets may allow certain types of ICMP (host unreachable, port unreachable) which are useful for UDP ping attempts.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-298 on capec.mitre.org](https://capec.mitre.org/data/definitions/298.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
