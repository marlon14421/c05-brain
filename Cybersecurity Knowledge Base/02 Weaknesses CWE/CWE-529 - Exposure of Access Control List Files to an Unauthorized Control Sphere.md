---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-529"
status: "Incomplete"
---
# CWE-529: Exposure of Access Control List Files to an Unauthorized Control Sphere

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product stores access control list files in a directory or other container that is accessible to actors outside of the intended control sphere.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Protect access control list files.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-529 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/529.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
