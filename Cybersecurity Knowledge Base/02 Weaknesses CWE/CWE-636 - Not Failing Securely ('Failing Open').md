---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-636"
status: "Draft"
---
# CWE-636: Not Failing Securely ('Failing Open')

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, ICS/OT

## Description

When the product encounters an error condition or failure, its design requires it to fall back to a state that is less secure than other options that are available, such as selecting the weakest encryption algorithm or using the most permissive access control restrictions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Subdivide and allocate resources and components so that a failure in one part does not affect the entire product.

## Related weaknesses

- CWE-657 (ChildOf)
- CWE-755 (ChildOf)
- CWE-280 (PeerOf)

## Source

- [CWE-636 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/636.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
