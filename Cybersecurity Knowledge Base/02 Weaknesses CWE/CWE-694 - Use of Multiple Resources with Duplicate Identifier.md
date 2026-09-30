---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-694"
status: "Incomplete"
---
# CWE-694: Use of Multiple Resources with Duplicate Identifier

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses multiple resources that can have the same identifier, in a context in which unique identifiers are required.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Where possible, use unique identifiers. If non-unique identifiers are detected, then do not operate any resource with a non-unique identifier and report the error appropriately.

## Related weaknesses

- CWE-99 (ChildOf)
- CWE-573 (ChildOf)

## Source

- [CWE-694 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/694.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
