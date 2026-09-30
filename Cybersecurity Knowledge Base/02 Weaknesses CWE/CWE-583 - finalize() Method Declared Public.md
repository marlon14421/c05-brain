---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-583"
status: "Incomplete"
---
# CWE-583: finalize() Method Declared Public

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java

## Description

The product violates secure coding principles for mobile code by declaring a finalize() method public.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If you are using finalize() as it was designed, there is no reason to declare finalize() with anything other than protected access.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-583 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/583.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
