---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-311"
status: "Draft"
---
# CWE-311: Missing Encryption of Sensitive Data

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not encrypt sensitive or critical information before storage or transmission.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Clearly specify which data or resources are valuable enough that they should be protected by encryption. Require that any transmission or storage of this data/resource should use well-vetted encryption algorithms.
- **Implementation:** When using industry-approved techniques, use them correctly. Don't cut corners by skipping resource-intensive steps (CWE-325). These steps are often essential for preventing common attacks.
- **Implementation:** Use naming conventions and strong types to make it easier to spot when sensitive data is being used. When creating structures, objects, or other complex entities, separate the sensitive and non-sensitive data as much as possible.

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-311 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/311.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
