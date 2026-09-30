---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-549"
status: "Draft"
---
# CWE-549: Missing Password Field Masking

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

The product does not mask passwords during entry, increasing the potential for attackers to observe and capture passwords.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Recommendations include requiring all password fields in your web application be masked to prevent other users from seeing this information.

## Related weaknesses

- CWE-522 (ChildOf)

## Source

- [CWE-549 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/549.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
