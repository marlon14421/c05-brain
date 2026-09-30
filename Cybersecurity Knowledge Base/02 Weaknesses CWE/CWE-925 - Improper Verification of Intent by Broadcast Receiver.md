---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-925"
status: "Incomplete"
---
# CWE-925: Improper Verification of Intent by Broadcast Receiver

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Mobile

## Description

The Android application uses a Broadcast Receiver that receives an Intent but does not properly verify that the Intent came from an authorized source.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Before acting on the Intent, check the Intent Action to make sure it matches the expected System action.

## Related weaknesses

- CWE-940 (ChildOf)

## Source

- [CWE-925 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/925.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
