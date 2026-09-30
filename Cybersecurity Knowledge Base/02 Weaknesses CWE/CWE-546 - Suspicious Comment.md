---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-546"
status: "Draft"
---
# CWE-546: Suspicious Comment

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The code contains comments that suggest the presence of bugs, incomplete functionality, or weaknesses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Documentation:** Remove comments that suggest the presence of bugs, incomplete functionality, or weaknesses, before deploying the application.

## Related weaknesses

- CWE-1078 (ChildOf)

## Source

- [CWE-546 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/546.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
