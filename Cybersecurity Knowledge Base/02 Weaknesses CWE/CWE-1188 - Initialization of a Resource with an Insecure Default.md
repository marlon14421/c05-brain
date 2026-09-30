---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1188"
status: "Incomplete"
---
# CWE-1188: Initialization of a Resource with an Insecure Default

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product initializes or sets a resource with a default that is intended to be changed by the product's installer, administrator, or maintainer, but the default is not secure.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-1419 (ChildOf)
- CWE-344 (ChildOf)
- CWE-665 (ChildOf)

## Source

- [CWE-1188 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1188.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
