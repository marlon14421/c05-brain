---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0546"
target_object: "T1082"
stix_relationship_id: "relationship--9e85e741-0dcd-4a15-a35a-a920f46824c2"
---
# Relationship 8557: S0546 — uses → T1082

**Source object:** [[01 ATT&CK/S0546 - SharpStage|S0546: SharpStage]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpStage](https://attack.mitre.org/software/S0546) has checked the system settings to see if Arabic is the configured language.(Citation: BleepingComputer Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e85e741-0dcd-4a15-a35a-a920f46824c2`.
