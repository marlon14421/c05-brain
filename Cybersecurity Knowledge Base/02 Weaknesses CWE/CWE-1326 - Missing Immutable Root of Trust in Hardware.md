---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1326"
status: "Draft"
---
# CWE-1326: Missing Immutable Root of Trust in Hardware

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Security Hardware, Not Technology-Specific

## Description

A missing immutable root of trust in the hardware results in the ability to bypass secure boot or execute untrusted or adversarial boot code.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When architecting the system, the RoT should be designated for storage in a memory that does not allow further programming/writes.
- **Implementation:** During implementation and test, the RoT memory location should be demonstrated to not allow further programming/writes.

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-1326 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1326.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
