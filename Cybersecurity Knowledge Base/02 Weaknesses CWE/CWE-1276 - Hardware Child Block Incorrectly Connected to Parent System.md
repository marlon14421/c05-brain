---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1276"
status: "Incomplete"
---
# CWE-1276: Hardware Child Block Incorrectly Connected to Parent System

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

Signals between a hardware IP and the parent system design are incorrectly connected causing security risks.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** System-level verification may be used to ensure that components are correctly connected and that design security requirements are not violated due to interactions between various IP blocks.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1276 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1276.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
