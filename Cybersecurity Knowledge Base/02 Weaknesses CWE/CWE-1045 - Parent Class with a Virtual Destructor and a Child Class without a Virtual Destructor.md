---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1045"
status: "Incomplete"
---
# CWE-1045: Parent Class with a Virtual Destructor and a Child Class without a Virtual Destructor

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

A parent class has a virtual destructor method, but the parent has a child class that does not have a virtual destructor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-1076 (ChildOf)

## Source

- [CWE-1045 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1045.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
