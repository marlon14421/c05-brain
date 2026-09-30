---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1183"
target_object: "T1059.003"
stix_relationship_id: "relationship--6d82c047-f175-4efe-8380-099da617bf01"
---
# Relationship 8478: S1183 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1183 - StrelaStealer|S1183: StrelaStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) has included BAT files in some instances for installation.(Citation: Fortgale StrelaStealer 2023)(Citation: IBM StrelaStealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d82c047-f175-4efe-8380-099da617bf01`.
