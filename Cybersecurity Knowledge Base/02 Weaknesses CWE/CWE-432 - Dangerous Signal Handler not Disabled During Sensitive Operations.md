---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-432"
status: "Draft"
---
# CWE-432: Dangerous Signal Handler not Disabled During Sensitive Operations

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses a signal handler that shares state with other signal handlers, but it does not properly mask or prevent those signal handlers from being invoked while the original signal handler is still running.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Turn off dangerous handlers when performing sensitive operations.

## Related weaknesses

- CWE-364 (ChildOf)

## Source

- [CWE-432 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/432.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
