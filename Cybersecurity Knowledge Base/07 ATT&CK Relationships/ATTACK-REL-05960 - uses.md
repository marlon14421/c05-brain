---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1182"
target_object: "T1016"
stix_relationship_id: "relationship--79c99261-dae6-4cd8-90b3-bf60fd57d5c9"
---
# Relationship 5960: S1182 — uses → T1016

**Source object:** [[01 ATT&CK/S1182 - MagicRAT|S1182: MagicRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MagicRAT](https://attack.mitre.org/software/S1182) collects system network information using commands such as `ipconfig /all`.(Citation: Cisco MagicRAT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79c99261-dae6-4cd8-90b3-bf60fd57d5c9`.
