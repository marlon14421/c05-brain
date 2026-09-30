---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-130"
status: "Incomplete"
---
# CWE-130: Improper Handling of Length Parameter Inconsistency

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++, Not Language-Specific, Not Technology-Specific

## Description

The product parses a formatted message or structure, but it does not handle or incorrectly handles a length field that is inconsistent with the actual length of the associated data.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When processing structured incoming data containing a size field followed by raw data, ensure that you identify and resolve any inconsistencies between the size field and the actual size of the data.
- **Implementation:** Do not let the user control the size of the buffer.
- **Implementation:** Validate that the length of the user-supplied data is consistent with the buffer size.

## Related weaknesses

- CWE-240 (ChildOf)
- CWE-119 (ChildOf)
- CWE-119 (ChildOf)
- CWE-805 (CanPrecede)

## Source

- [CWE-130 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/130.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
