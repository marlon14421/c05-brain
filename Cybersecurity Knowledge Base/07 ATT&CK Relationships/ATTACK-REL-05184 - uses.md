---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1044"
target_object: "T1120"
stix_relationship_id: "relationship--1555866c-1eca-4de3-aded-d745fdd47d1c"
---
# Relationship 5184: S1044 — uses → T1120

**Source object:** [[01 ATT&CK/S1044 - FunnyDream|S1044: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [FunnyDream](https://attack.mitre.org/software/S1044) FilepakMonitor component can detect removable drive insertion.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1555866c-1eca-4de3-aded-d745fdd47d1c`.
