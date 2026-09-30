---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1036"
target_object: "T1027.013"
stix_relationship_id: "relationship--faa996f9-3d60-455f-ab31-50687113f24e"
---
# Relationship 7243: G1036 — uses → T1027.013

**Source object:** [[01 ATT&CK/G1036 - Moonstone Sleet|G1036: Moonstone Sleet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Moonstone Sleet](https://attack.mitre.org/groups/G1036) has used encrypted payloads within files for follow-on execution and defense evasion.(Citation: Microsoft Moonstone Sleet 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--faa996f9-3d60-455f-ab31-50687113f24e`.
