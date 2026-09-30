---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-277"
status: "Draft"
---
# CWE-277: Insecure Inherited Permissions

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A product defines a set of insecure permissions that are inherited by objects that are created by the program.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.

## Related weaknesses

- CWE-732 (ChildOf)

## Source

- [CWE-277 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/277.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
