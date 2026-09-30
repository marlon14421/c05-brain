---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0607"
target_object: "T1057"
stix_relationship_id: "relationship--75c7794b-e8e1-4fcb-b59a-14eb710c47f7"
---
# Relationship 9552: S0607 — uses → T1057

**Source object:** [[01 ATT&CK/S0607 - KillDisk|S0607: KillDisk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KillDisk](https://attack.mitre.org/software/S0607) has called GetCurrentProcess .(Citation: Trend Micro KillDisk 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75c7794b-e8e1-4fcb-b59a-14eb710c47f7`.
