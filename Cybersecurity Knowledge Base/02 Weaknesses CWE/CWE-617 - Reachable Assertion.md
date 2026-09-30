---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-617"
status: "Draft"
---
# CWE-617: Reachable Assertion

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, C, Java, Rust, Not Technology-Specific

## Description

The product contains an assert() or similar statement that can be triggered by an attacker, which leads to an application exit or other behavior that is more severe than necessary.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Make sensitive open/close operation non reachable by directly user-controlled data (e.g. open/close resources)
- **Implementation:** Perform input validation on user data.

## Related weaknesses

- CWE-705 (ChildOf)
- CWE-670 (ChildOf)

## Source

- [CWE-617 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/617.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
