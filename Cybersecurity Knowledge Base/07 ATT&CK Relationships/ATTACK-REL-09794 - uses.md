---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1196"
target_object: "T1074.001"
stix_relationship_id: "relationship--11fdff9c-078b-48f6-ac6c-4a2c89dafc4f"
---
# Relationship 9794: S1196 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1196 - Troll Stealer|S1196: Troll Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Troll Stealer](https://attack.mitre.org/software/S1196) encrypts gathered information on victim devices prior to exfiltrating it through command and control infrastructure.(Citation: S2W Troll Stealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11fdff9c-078b-48f6-ac6c-4a2c89dafc4f`.
