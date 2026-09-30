---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0372"
target_object: "T1553.002"
stix_relationship_id: "relationship--c035989f-a86f-4746-a9d4-3286dc68e473"
---
# Relationship 6672: S0372 — uses → T1553.002

**Source object:** [[01 ATT&CK/S0372 - LockerGoga|S0372: LockerGoga]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockerGoga](https://attack.mitre.org/software/S0372) has been signed with stolen certificates in order to make it look more legitimate.(Citation: Wired Lockergoga 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c035989f-a86f-4746-a9d4-3286dc68e473`.
