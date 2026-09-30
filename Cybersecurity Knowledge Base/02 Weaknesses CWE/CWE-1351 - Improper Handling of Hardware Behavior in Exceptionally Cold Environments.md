---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1351"
status: "Incomplete"
---
# CWE-1351: Improper Handling of Hardware Behavior in Exceptionally Cold Environments

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Embedded, Microcomputer, System on Chip

## Description

A hardware device, or the firmware running on it, is missing or has incorrect protection features to maintain goals of security primitives when the device is cooled below standard operating temperatures.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The system should account for security primitive behavior when cooled outside standard temperatures.

## Related weaknesses

- CWE-1384 (ChildOf)

## Source

- [CWE-1351 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1351.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
