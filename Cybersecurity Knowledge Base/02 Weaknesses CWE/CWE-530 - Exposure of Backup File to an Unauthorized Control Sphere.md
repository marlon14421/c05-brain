---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-530"
status: "Incomplete"
---
# CWE-530: Exposure of Backup File to an Unauthorized Control Sphere

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Server

## Description

A backup file is stored in a directory or archive that is made accessible to unauthorized actors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Policy:** Recommendations include implementing a security policy within your organization that prohibits backing up web application source code in the webroot.

## Related weaknesses

- CWE-552 (ChildOf)

## Source

- [CWE-530 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/530.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
