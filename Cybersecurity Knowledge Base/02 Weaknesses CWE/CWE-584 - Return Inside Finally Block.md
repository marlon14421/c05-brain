---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-584"
status: "Draft"
---
# CWE-584: Return Inside Finally Block

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The code has a return statement inside a finally block, which will cause any thrown exception in the try block to be discarded.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not use a return statement inside the finally block. The finally block should have "cleanup" code.

## Related weaknesses

- CWE-705 (ChildOf)

## Source

- [CWE-584 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/584.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
