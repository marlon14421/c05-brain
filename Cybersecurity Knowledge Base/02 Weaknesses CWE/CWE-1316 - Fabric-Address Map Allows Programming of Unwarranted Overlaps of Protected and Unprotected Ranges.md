---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1316"
status: "Draft"
---
# CWE-1316: Fabric-Address Map Allows Programming of Unwarranted Overlaps of Protected and Unprotected Ranges

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Bus/Interface Hardware, Not Technology-Specific

## Description

The address map of the on-chip fabric has protected and unprotected regions overlapping, allowing an attacker to bypass access control to the overlapping portion of the protected region.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When architecting the address map of the chip, ensure that protected and unprotected ranges are isolated and do not overlap. When designing, ensure that ranges hardcoded in Register-Transfer Level (RTL) do not overlap.
- **Implementation:** Ranges configured by firmware should not overlap. If overlaps are mandatory because of constraints such as a limited number of registers, then ensure that no assets are present in the overlapped portion.
- **Testing:** Validate mitigation actions with robust testing.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1316 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1316.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
