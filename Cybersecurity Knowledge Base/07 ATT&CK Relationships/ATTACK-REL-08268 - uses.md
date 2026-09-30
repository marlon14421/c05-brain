---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0114"
target_object: "T1018"
stix_relationship_id: "relationship--d45cd2ee-f0f6-417a-98c2-9a7e9f6dc480"
---
# Relationship 8268: G0114 — uses → T1018

**Source object:** [[01 ATT&CK/G0114 - Chimera|G0114: Chimera]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chimera](https://attack.mitre.org/groups/G0114) has utilized various scans and queries to find domain controllers and remote services in the target environment.(Citation: NCC Group Chimera January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d45cd2ee-f0f6-417a-98c2-9a7e9f6dc480`.
