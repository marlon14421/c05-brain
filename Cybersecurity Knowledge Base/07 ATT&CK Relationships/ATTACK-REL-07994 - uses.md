---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1141"
target_object: "T1560.001"
stix_relationship_id: "relationship--58401f64-b536-4a3c-a1e4-2c0d2da8db19"
---
# Relationship 7994: S1141 — uses → T1560.001

**Source object:** [[01 ATT&CK/S1141 - LunarWeb|S1141: LunarWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LunarWeb](https://attack.mitre.org/software/S1141) can create a ZIP archive with specified files and directories.(Citation: ESET Turla Lunar toolset May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--58401f64-b536-4a3c-a1e4-2c0d2da8db19`.
