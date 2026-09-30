---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-375"
status: "Draft"
---
# CWE-375: Returning a Mutable Object to an Untrusted Caller

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Object-Oriented, C, C++, Java, C#

## Description

Sending non-cloned mutable data as a return value may result in that data being altered or deleted by the calling function.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Declare returned data which should not be altered as constant or immutable.
- **Implementation:** Clone all mutable data before returning references to it. This is the preferred mitigation. This way, regardless of what changes are made to the data, a valid copy is retained for use by the class.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-375 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/375.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
