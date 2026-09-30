---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-552"
status: "Draft"
---
# CWE-552: Files or Directories Accessible to External Parties

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Cloud Computing

## Description

The product makes files or directories accessible to unauthorized actors, even though they should not be.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When storing data in the cloud (e.g., S3 buckets, Azure blobs, Google Cloud Storage, etc.), use the provider's controls to disable public access.

## Related weaknesses

- CWE-668 (ChildOf)
- CWE-668 (ChildOf)
- CWE-285 (ChildOf)

## Source

- [CWE-552 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/552.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
