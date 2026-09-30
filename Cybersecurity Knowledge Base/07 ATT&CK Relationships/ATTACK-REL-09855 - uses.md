---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1182"
target_object: "T1027.013"
stix_relationship_id: "relationship--600524be-d3c3-4f59-b257-0f3d868b9e1a"
---
# Relationship 9855: S1182 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1182 - MagicRAT|S1182: MagicRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MagicRAT](https://attack.mitre.org/software/S1182) stores base64 encoded command and contorl URLs in a configuraiton file, with each URL prefixed with the value `LR02DPt22R`.(Citation: Cisco MagicRAT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--600524be-d3c3-4f59-b257-0f3d868b9e1a`.
