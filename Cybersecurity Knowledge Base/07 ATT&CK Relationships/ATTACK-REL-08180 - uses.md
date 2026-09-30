---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0044"
target_object: "T1584.004"
stix_relationship_id: "relationship--f8f41001-9fc7-4a19-99e8-2b915abccf52"
---
# Relationship 8180: C0044 — uses → T1584.004

**Source object:** [[01 ATT&CK/C0044 - Juicy Mix|C0044: Juicy Mix]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.004 - Server|T1584.004: Server]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Juicy Mix](https://attack.mitre.org/campaigns/C0044), [OilRig](https://attack.mitre.org/groups/G0049) compromised an Israeli job portal to use for a C2 server.(Citation: ESET OilRig Campaigns Sep 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8f41001-9fc7-4a19-99e8-2b915abccf52`.
