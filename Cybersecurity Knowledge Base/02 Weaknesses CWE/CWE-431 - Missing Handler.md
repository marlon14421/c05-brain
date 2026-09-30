---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-431"
status: "Draft"
---
# CWE-431: Missing Handler

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A handler is not available or implemented.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Handle all possible situations (e.g. error condition).
- **Implementation:** If an operation can throw an Exception, implement a handler for that specific exception.

## Related weaknesses

- CWE-691 (ChildOf)
- CWE-433 (CanPrecede)

## Source

- [CWE-431 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/431.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
