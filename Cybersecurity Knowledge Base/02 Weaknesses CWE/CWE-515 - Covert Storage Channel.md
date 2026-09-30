---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-515"
status: "Incomplete"
---
# CWE-515: Covert Storage Channel

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

A covert storage channel transfers information through the setting of bits by one program and the reading of those bits by another. What distinguishes this case from that of ordinary operation is that the bits are used to convey encoded information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that all reserved fields are set to zero before messages are sent and that no unnecessary information is included.

## Related weaknesses

- CWE-514 (ChildOf)

## Source

- [CWE-515 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/515.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
