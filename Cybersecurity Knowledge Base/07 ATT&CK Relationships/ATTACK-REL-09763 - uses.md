---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1050"
target_object: "T1218.011"
stix_relationship_id: "relationship--8925d506-5fa7-4d8d-82bd-09c650029469"
---
# Relationship 9763: S1050 — uses → T1218.011

**Source object:** [[01 ATT&CK/S1050 - PcShare|S1050: PcShare]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PcShare](https://attack.mitre.org/software/S1050) has used `rundll32.exe` for execution.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8925d506-5fa7-4d8d-82bd-09c650029469`.
