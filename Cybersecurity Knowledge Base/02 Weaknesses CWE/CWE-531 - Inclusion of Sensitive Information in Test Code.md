---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-531"
status: "Incomplete"
---
# CWE-531: Inclusion of Sensitive Information in Test Code

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

Accessible test applications can pose a variety of security risks. Since developers or administrators rarely consider that someone besides themselves would even know about the existence of these applications, it is common for them to contain sensitive information or functions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Distribution:** Remove test code before deploying the application into production.

## Related weaknesses

- CWE-540 (ChildOf)

## Source

- [CWE-531 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/531.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
