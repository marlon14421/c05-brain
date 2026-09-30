---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1245"
status: "Incomplete"
---
# CWE-1245: Improper Finite State Machines (FSMs) in Hardware Logic

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Description

Faulty finite state machines (FSMs) in the hardware logic allow an attacker to put the system in an undefined state, to cause a denial of service (DoS) or gain privileges on the victim's system.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Define all possible states and handle all unused states through default statements. Ensure that system defaults to a secure state.

## Related weaknesses

- CWE-684 (ChildOf)

## Source

- [CWE-1245 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1245.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
