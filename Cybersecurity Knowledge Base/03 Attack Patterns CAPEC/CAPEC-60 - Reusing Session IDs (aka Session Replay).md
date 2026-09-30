---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-60"
status: "Draft"
---
# CAPEC-60: Reusing Session IDs (aka Session Replay)

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** High

## Description

This attack targets the reuse of valid session ID to spoof the target system in order to gain privileges. The attacker tries to reuse a stolen session ID used previously during a transaction to perform spoofing and session hijacking. Another name for this type of attack is Session Replay.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-60 on capec.mitre.org](https://capec.mitre.org/data/definitions/60.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
