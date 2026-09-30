---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-323"
status: "Stable"
---
# CAPEC-323: TCP (ISN) Counter Rate Probe

**Abstraction:** Detailed  
**Catalog severity:** Low  
**Catalog likelihood:** Medium

## Description

This OS detection probe measures the average rate of initial sequence number increments during a period of time. Sequence numbers are incremented using a time-based algorithm and are susceptible to a timing analysis that can determine the number of increments per unit time. The result of this analysis is then compared against a database of operating systems and versions to determine likely operation system matches.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-323 on capec.mitre.org](https://capec.mitre.org/data/definitions/323.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
