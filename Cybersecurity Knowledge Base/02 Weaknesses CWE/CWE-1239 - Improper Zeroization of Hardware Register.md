---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1239"
status: "Draft"
---
# CWE-1239: Improper Zeroization of Hardware Register

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Description

The hardware product does not properly clear sensitive information from built-in registers when the user of the hardware block changes.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Every register potentially containing sensitive information must have a policy specifying how and when information is cleared, in addition to clarifying if it is the responsibility of the hardware logic or IP user to initiate the zeroization procedure at the appropriate time.

## Related weaknesses

- CWE-226 (ChildOf)
- CWE-226 (ChildOf)

## Source

- [CWE-1239 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1239.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
