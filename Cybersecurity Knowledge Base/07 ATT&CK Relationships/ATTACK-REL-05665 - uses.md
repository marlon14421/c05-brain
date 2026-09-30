---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0093"
target_object: "T1033"
stix_relationship_id: "relationship--d2d9a619-4379-4e15-9115-40ca9209f316"
---
# Relationship 5665: S0093 — uses → T1033

**Source object:** [[01 ATT&CK/S0093 - Backdoor.Oldrea|S0093: Backdoor.Oldrea]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Backdoor.Oldrea](https://attack.mitre.org/software/S0093) collects the current username from the victim.(Citation: Symantec Dragonfly)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2d9a619-4379-4e15-9115-40ca9209f316`.
