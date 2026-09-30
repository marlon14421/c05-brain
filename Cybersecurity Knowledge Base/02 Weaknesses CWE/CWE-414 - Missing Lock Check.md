---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-414"
status: "Draft"
---
# CWE-414: Missing Lock Check

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A product does not check to see if a lock is present before performing sensitive operations on a resource.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Implement a reliable lock mechanism.

## Related weaknesses

- CWE-667 (ChildOf)

## Source

- [CWE-414 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/414.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
