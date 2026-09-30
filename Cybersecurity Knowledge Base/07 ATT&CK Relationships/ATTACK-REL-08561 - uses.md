---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0576"
target_object: "T1497.001"
stix_relationship_id: "relationship--3cf330d6-3a3c-437f-922b-c1bdce852b71"
---
# Relationship 8561: S0576 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0576 - MegaCortex|S0576: MegaCortex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MegaCortex](https://attack.mitre.org/software/S0576) has checked the number of CPUs in the system to avoid being run in a sandbox or emulator.(Citation: IBM MegaCortex)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cf330d6-3a3c-437f-922b-c1bdce852b71`.
