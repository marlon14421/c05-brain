---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-326"
status: "Draft"
---
# CWE-326: Inadequate Encryption Strength

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product stores or transmits sensitive data using an encryption scheme that is theoretically sound, but is not strong enough for the level of protection required.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use an encryption scheme that is currently considered to be strong by experts in the field.

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-326 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/326.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
