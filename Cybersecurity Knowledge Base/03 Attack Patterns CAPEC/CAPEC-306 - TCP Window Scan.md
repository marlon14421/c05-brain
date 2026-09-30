---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-306"
status: "Stable"
---
# CAPEC-306: TCP Window Scan

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Not stated

## Description

An adversary engages in TCP Window scanning to analyze port status and operating system type. TCP Window scanning uses the ACK scanning method but examine the TCP Window Size field of response RST packets to make certain inferences. While TCP Window Scans are fast and relatively stealthy, they work against fewer TCP stack implementations than any other type of scan. Some operating systems return a positive TCP window size when a RST packet is sent from an open port, and a negative value when the RST originates from a closed port. TCP Window scanning is one of the most complex scan types, and its results are difficult to interpret. Window scanning alone rarely yields useful information, but when combined with other types of scanning is more useful. It is a generally more reliable means of making inference about operating system versions than port status.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-306 on capec.mitre.org](https://capec.mitre.org/data/definitions/306.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
