---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-767"
status: "Incomplete"
---
# CWE-767: Access to Critical Private Variable via Public Method

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C++, C#, Java

## Description

The product defines a public method that reads or modifies a private variable.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use class accessor and mutator methods appropriately. Perform validation when accepting data from a public method that is intended to modify a critical private variable. Also be sure that appropriate access controls are being applied when a public method interfaces with critical data.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-767 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/767.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
