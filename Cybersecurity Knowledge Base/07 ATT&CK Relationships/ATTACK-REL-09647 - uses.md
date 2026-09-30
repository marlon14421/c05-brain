---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0025"
target_object: "T1554"
stix_relationship_id: "relationship--e51f5310-3508-4a79-8f3e-3a02f5d685e8"
---
# Relationship 9647: C0025 — uses → T1554

**Source object:** [[01 ATT&CK/C0025 - 2016 Ukraine Electric Power Attack|C0025: 2016 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2016 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0025), [Sandworm Team](https://attack.mitre.org/groups/G0034) used a trojanized version of Windows Notepad to add a layer of persistence for [Industroyer](https://attack.mitre.org/software/S0604).(Citation: ESET Industroyer)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e51f5310-3508-4a79-8f3e-3a02f5d685e8`.
