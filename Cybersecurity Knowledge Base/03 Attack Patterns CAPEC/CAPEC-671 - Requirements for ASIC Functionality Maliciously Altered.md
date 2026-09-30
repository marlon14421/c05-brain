---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-671"
status: "Draft"
---
# CAPEC-671: Requirements for ASIC Functionality Maliciously Altered

**Abstraction:** Detailed  
**Catalog severity:** High  
**Catalog likelihood:** Low

## Description

An adversary with access to functional requirements for an application specific integrated circuit (ASIC), a chip designed/customized for a singular particular use, maliciously alters requirements derived from originating capability needs. In the chip manufacturing process, requirements drive the chip design which, when the chip is fully manufactured, could result in an ASIC which may not meet the user’s needs, contain malicious functionality, or exhibit other anomalous behaviors thereby affecting the intended use of the ASIC.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-671 on capec.mitre.org](https://capec.mitre.org/data/definitions/671.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
