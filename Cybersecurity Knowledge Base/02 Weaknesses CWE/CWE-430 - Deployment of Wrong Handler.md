---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-430"
status: "Incomplete"
---
# CWE-430: Deployment of Wrong Handler

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The wrong "handler" is assigned to process an object.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Perform a type check before interpreting an object.
- **Architecture and Design:** Reject any inconsistent types, such as a file with a .GIF extension that appears to consist of PHP code.

## Related weaknesses

- CWE-691 (ChildOf)
- CWE-433 (CanPrecede)
- CWE-434 (PeerOf)

## Source

- [CWE-430 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/430.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
