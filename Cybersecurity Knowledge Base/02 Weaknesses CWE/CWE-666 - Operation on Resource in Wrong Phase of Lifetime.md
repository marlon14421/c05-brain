---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-666"
status: "Draft"
---
# CWE-666: Operation on Resource in Wrong Phase of Lifetime

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product performs an operation on a resource at the wrong phase of the resource's lifecycle, which can lead to unexpected behaviors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Follow the resource's lifecycle from creation to release.

## Related weaknesses

- CWE-664 (ChildOf)

## Source

- [CWE-666 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/666.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
