---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-453"
status: "Draft"
---
# CWE-453: Insecure Default Variable Initialization

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** PHP, Not Language-Specific

## Description

The product, by default, initializes an internal variable with an insecure or less secure value than is possible.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Disable or change default settings when they can be used to abuse the system. Since those default settings are shipped with the product they are likely to be known by a potential attacker who is familiar with the product. For instance, default credentials should be changed or the associated accounts should be disabled.

## Related weaknesses

- CWE-1188 (ChildOf)

## Source

- [CWE-453 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/453.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
