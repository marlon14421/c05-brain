---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0091"
target_object: "T1021.001"
stix_relationship_id: "relationship--5cc793b0-cc45-439e-a994-c8884ca55fe7"
---
# Relationship 7536: G0091 — uses → T1021.001

**Source object:** [[01 ATT&CK/G0091 - Silence|G0091: Silence]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.001 - Remote Desktop Protocol|T1021.001: Remote Desktop Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Silence](https://attack.mitre.org/groups/G0091) has used RDP for lateral movement.(Citation: Group IB Silence Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5cc793b0-cc45-439e-a994-c8884ca55fe7`.
