---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0546"
target_object: "T1053.005"
stix_relationship_id: "relationship--31fe18d1-7799-466c-adb3-3be923ed4f3a"
---
# Relationship 6857: S0546 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0546 - SharpStage|S0546: SharpStage]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpStage](https://attack.mitre.org/software/S0546) has a persistence component to write a scheduled task for the payload.(Citation: Cybereason Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31fe18d1-7799-466c-adb3-3be923ed4f3a`.
