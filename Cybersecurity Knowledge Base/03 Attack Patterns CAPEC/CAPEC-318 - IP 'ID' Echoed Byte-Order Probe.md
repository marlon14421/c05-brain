---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-318"
status: "Stable"
---
# CAPEC-318: IP 'ID' Echoed Byte-Order Probe

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

This OS fingerprinting probe tests to determine if the remote host echoes back the IP 'ID' value from the probe packet. An attacker sends a UDP datagram with an arbitrary IP 'ID' value to a closed port on the remote host to observe the manner in which this bit is echoed back in the ICMP error message. The identification field (ID) is typically utilized for reassembling a fragmented packet. Some operating systems or router firmware reverse the bit order of the ID field when echoing the IP Header portion of the original datagram within an ICMP error message.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-318 on capec.mitre.org](https://capec.mitre.org/data/definitions/318.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
