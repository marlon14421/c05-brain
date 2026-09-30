---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1036"
target_object: "T1598.003"
stix_relationship_id: "relationship--b5d1e525-1bb7-43a9-8cb6-0a8d9539b465"
---
# Relationship 9150: G1036 — uses → T1598.003

**Source object:** [[01 ATT&CK/G1036 - Moonstone Sleet|G1036: Moonstone Sleet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1598.003 - Spearphishing Link|T1598.003: Spearphishing Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Moonstone Sleet](https://attack.mitre.org/groups/G1036) used spearphishing messages containing items such as tracking pixels to determine if users interacted with malicious messages.(Citation: Microsoft Moonstone Sleet 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5d1e525-1bb7-43a9-8cb6-0a8d9539b465`.
