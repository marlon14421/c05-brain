---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1310"
status: "Draft"
---
# CWE-1310: Missing Ability to Patch ROM Code

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Description

Missing an ability to patch ROM code may leave a System or System-on-Chip (SoC) in a vulnerable state.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Secure patch support to allow ROM code to be patched on the next boot.
- **Architecture and Design:** Support patches that can be programmed in-field or during manufacturing through hardware fuses. This feature can be used for limited patching of devices after shipping, or for the next batch of silicon devices manufactured, without changing the full device ROM.

## Related weaknesses

- CWE-1329 (ChildOf)

## Source

- [CWE-1310 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1310.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
