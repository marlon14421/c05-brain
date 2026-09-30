---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-276"
status: "Draft"
---
# CWE-276: Incorrect Default Permissions

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, ICS/OT

## Description

During installation, installed file permissions are set to allow anyone to modify those files.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The architecture needs to access and modification attributes for files to only those users who actually require those actions.

## Related weaknesses

- CWE-732 (ChildOf)
- CWE-732 (ChildOf)

## Source

- [CWE-276 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/276.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
