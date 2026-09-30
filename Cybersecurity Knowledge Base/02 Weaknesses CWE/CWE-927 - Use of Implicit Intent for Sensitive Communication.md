---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-927"
status: "Incomplete"
---
# CWE-927: Use of Implicit Intent for Sensitive Communication

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Mobile

## Description

The Android application uses an implicit intent for transmitting sensitive data to other applications.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If the application only requires communication with its own components, then the destination is always known, and an explicit intent could be used.

## Related weaknesses

- CWE-285 (ChildOf)
- CWE-668 (ChildOf)

## Source

- [CWE-927 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/927.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
