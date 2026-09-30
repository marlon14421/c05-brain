---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1282"
status: "Incomplete"
---
# CWE-1282: Assumed-Immutable Data is Stored in Writable Memory

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

Immutable data, such as a first-stage bootloader, device identifiers, and "write-once" configuration settings are stored in writable memory that can be re-programmed or updated in the field.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** All immutable code or data should be programmed into ROM or write-once memory.

## Related weaknesses

- CWE-668 (ChildOf)
- CWE-471 (CanPrecede)

## Source

- [CWE-1282 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1282.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
