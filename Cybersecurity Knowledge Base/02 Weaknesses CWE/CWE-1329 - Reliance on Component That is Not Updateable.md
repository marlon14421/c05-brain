---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1329"
status: "Incomplete"
---
# CWE-1329: Reliance on Component That is Not Updateable

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific, ICS/OT

## Description

The product contains a component that cannot be updated or patched in order to remove vulnerabilities or significant bugs.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Specify requirements that each component should be updateable, including ROM, firmware, etc.
- **Architecture and Design:** Design the product to allow for updating of its components. Include the external infrastructure that might be necessary to support updates, such as distribution servers.
- **Architecture and Design:** With hardware, support patches that can be programmed in-field or during manufacturing through hardware fuses. This feature can be used for limited patching of devices after shipping, or for the next batch of silicon devices manufactured, without changing the full device ROM.
- **Implementation:** Implement the necessary functionality to allow each component to be updated.

## Related weaknesses

- CWE-1357 (ChildOf)
- CWE-1357 (ChildOf)
- CWE-664 (ChildOf)

## Source

- [CWE-1329 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1329.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
