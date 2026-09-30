---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1257"
status: "Incomplete"
---
# CWE-1257: Improper Access Control Applied to Mirrored or Aliased Memory Regions

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Memory Hardware, Processor Hardware, Microcontroller Hardware, Network on Chip Hardware, System on Chip

## Description

Aliased or mirrored memory regions in hardware designs may have inconsistent read/write permissions enforced by the hardware. A possible result is that an untrusted agent is blocked from accessing a memory region but is not blocked from accessing the corresponding aliased memory region.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The checks should be applied for consistency access rights between primary memory regions and any mirrored or aliased memory regions. If different memory protection units (MPU) are protecting the aliased regions, their protected range definitions and policies should be synchronized.
- **Architecture and Design:** The controls that allow enabling memory aliases or changing the size of mapped memory regions should only be programmable by trusted software components.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-119 (CanPrecede)

## Source

- [CWE-1257 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1257.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
