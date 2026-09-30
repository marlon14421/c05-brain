---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1315"
status: "Incomplete"
---
# CWE-1315: Improper Setting of Bus Controlling Capability in Fabric End-point

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The bus controller enables bits in the fabric end-point to allow responder devices to control transactions on the fabric.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** For responder devices, the register bit in the fabric end-point that enables the bus controlling capability must be set to 0 by default. This bit should not be set during secure-boot flows. Also, writes to this register must be access-protected to prevent malicious modifications to obtain bus-controlling capability.
- **Implementation:** For responder devices, the register bit in the fabric end-point that enables the bus controlling capability must be set to 0 by default. This bit should not be set during secure-boot flows. Also, writes to this register must be access-protected to prevent malicious modifications to obtain bus-controlling capability.
- **System Configuration:** For responder devices, the register bit in the fabric end-point that enables the bus controlling capability must be set to 0 by default. This bit should not be set during secure-boot flows. Also, writes to this register must be access-protected to prevent malicious modifications to obtain bus-controlling capability.

## Related weaknesses

- CWE-284 (ChildOf)

## Source

- [CWE-1315 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1315.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
