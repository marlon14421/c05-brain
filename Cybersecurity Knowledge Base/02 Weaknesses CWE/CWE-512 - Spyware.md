---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-512"
status: "Incomplete"
---
# CWE-512: Spyware

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product collects personally identifiable information about a human user or the user's activities, but the product accesses this information using other resources besides itself, and it does not require that user's explicit approval or direct input into the product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Operation:** Use spyware detection and removal software.
- **Installation:** Always verify the integrity of the product that is being installed.

## Related weaknesses

- CWE-506 (ChildOf)

## Source

- [CWE-512 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/512.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
