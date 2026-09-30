---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0673"
target_object: "T1082"
stix_relationship_id: "relationship--ecb55914-837c-4600-a0f8-65d83d2d726b"
---
# Relationship 7711: S0673 — uses → T1082

**Source object:** [[01 ATT&CK/S0673 - DarkWatchman|S0673: DarkWatchman]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkWatchman](https://attack.mitre.org/software/S0673) can collect the OS version, system architecture, and computer name.(Citation: Prevailion DarkWatchman 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ecb55914-837c-4600-a0f8-65d83d2d726b`.
