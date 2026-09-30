---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1338"
status: "Draft"
---
# CWE-1338: Improper Protections Against Hardware Overheating

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific, ICS/OT, Power Management Hardware, Processor Hardware

## Description

A hardware device is missing or has inadequate protection features to prevent overheating.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Temperature maximum and minimum limits should be enforced using thermal sensors both in silicon and at the platform level.
- **Implementation:** The platform should support cooling solutions such as fans that can be modulated based on device-operation needs to maintain a stable temperature.

## Related weaknesses

- CWE-693 (ChildOf)

## Source

- [CWE-1338 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1338.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
