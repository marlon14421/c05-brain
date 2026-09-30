---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1256"
status: "Stable"
---
# CWE-1256: Improper Restriction of Software Interfaces to Hardware Features

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific, Memory Hardware, Power Management Hardware, Clock/Counter Hardware

## Description

The product provides software-controllable device functionality for capabilities such as power and clock management, but it does not properly limit functionality that can lead to modification of hardware memory or register bits, or the ability to observe physical side channels.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-285 (ChildOf)

## Source

- [CWE-1256 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1256.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
