---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-528"
status: "Draft"
---
# CWE-528: Exposure of Core Dump File to an Unauthorized Control Sphere

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product generates a core dump file in a directory, archive, or other resource that is stored, transferred, or otherwise made accessible to unauthorized actors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Protect the core dump files from unauthorized access.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-528 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/528.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
