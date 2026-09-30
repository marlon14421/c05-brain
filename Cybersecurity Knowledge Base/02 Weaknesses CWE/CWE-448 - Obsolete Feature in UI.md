---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-448"
status: "Draft"
---
# CWE-448: Obsolete Feature in UI

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A UI function is obsolete and the product does not warn the user.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Remove the obsolete feature from the UI. Warn the user that the feature is no longer supported.

## Related weaknesses

- CWE-446 (ChildOf)

## Source

- [CWE-448 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/448.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
