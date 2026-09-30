---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-471"
status: "Draft"
---
# CWE-471: Modification of Assumed-Immutable Data (MAID)

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

The product does not properly protect an assumed-immutable element from being modified by an attacker.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When the data is stored or transmitted through untrusted sources that could modify the data, implement integrity checks to detect unauthorized modification, or store/transmit the data in a trusted location that is free from external influence.

## Related weaknesses

- CWE-664 (ChildOf)

## Source

- [CWE-471 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/471.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
