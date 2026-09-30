---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1164"
status: "Incomplete"
---
# CWE-1164: Irrelevant Code

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product contains code that is not essential for execution, i.e. makes no state changes and has no side effects that alter data or control flow, such that removal of the code would have no impact to functionality or correctness.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-710 (ChildOf)

## Source

- [CWE-1164 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1164.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
