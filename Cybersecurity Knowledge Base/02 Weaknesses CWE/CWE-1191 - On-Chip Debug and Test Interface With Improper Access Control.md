---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1191"
status: "Stable"
---
# CWE-1191: On-Chip Debug and Test Interface With Improper Access Control

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The chip does not implement or does not correctly perform access control to check whether users are authorized to access internal registers and test modes through the physical debug/test interface.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** If feasible, the manufacturer should disable the JTAG interface or implement authentication and authorization for the JTAG interface. If authentication logic is added, it should be resistant to timing attacks. Security-sensitive data stored in registers, such as keys, etc. should be cleared when entering debug mode.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1191 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1191.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
