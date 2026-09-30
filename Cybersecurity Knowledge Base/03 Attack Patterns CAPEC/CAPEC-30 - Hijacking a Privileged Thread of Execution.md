---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-30"
status: "Draft"
---
# CAPEC-30: Hijacking a Privileged Thread of Execution

**Abstraction:** Standard  
**Catalog severity:** Very High  
**Catalog likelihood:** Low

## Description

An adversary hijacks a privileged thread of execution by injecting malicious code into a running process. By using a privleged thread to do their bidding, adversaries can evade process-based detection that would stop an attack that creates a new process. This can lead to an adversary gaining access to the process's memory and can also enable elevated privileges. The most common way to perform this attack is by suspending an existing thread and manipulating its memory.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-30 on capec.mitre.org](https://capec.mitre.org/data/definitions/30.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
