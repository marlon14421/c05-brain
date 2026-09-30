---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-75"
status: "Draft"
---
# CWE-75: Failure to Sanitize Special Elements into a Different Plane (Special Element Injection)

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not adequately filter user-controlled input for special elements with control implications.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Programming languages and supporting technologies might be chosen which are not subject to these issues.
- **Implementation:** Utilize an appropriate mix of allowlist and denylist parsing to filter special element syntax from all input.

## Related weaknesses

- CWE-74 (ChildOf)

## Source

- [CWE-75 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/75.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
