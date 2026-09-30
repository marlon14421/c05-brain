---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-538"
status: "Draft"
---
# CWE-538: Insertion of Sensitive Information into Externally-Accessible File or Directory

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product places sensitive information into files or directories that are accessible to actors who are allowed to have access to the files, but not to the sensitive information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Do not expose file and directory information to the user.

## Related weaknesses

- CWE-200 (ChildOf)

## Source

- [CWE-538 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/538.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
