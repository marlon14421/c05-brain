---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1142"
target_object: "T1074.001"
stix_relationship_id: "relationship--fca5e5e4-e615-44d5-901e-225fccd329cc"
---
# Relationship 7558: S1142 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1142 - LunarMail|S1142: LunarMail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LunarMail](https://attack.mitre.org/software/S1142) can create a directory in `%TEMP%\` to stage data prior to exfilration.(Citation: ESET Turla Lunar toolset May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fca5e5e4-e615-44d5-901e-225fccd329cc`.
