---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0546"
target_object: "T1614.001"
stix_relationship_id: "relationship--dbe09d1f-9826-448d-83e0-5712f575fe76"
---
# Relationship 5899: S0546 — uses → T1614.001

**Source object:** [[01 ATT&CK/S0546 - SharpStage|S0546: SharpStage]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpStage](https://attack.mitre.org/software/S0546) has been used to target Arabic-speaking users and used code that checks if the compromised machine has the Arabic language installed.(Citation: BleepingComputer Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dbe09d1f-9826-448d-83e0-5712f575fe76`.
