---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1566.003"
stix_relationship_id: "relationship--b3d6abc5-11da-4d0c-a699-8cafac03dfab"
---
# Relationship 5978: G0049 — uses → T1566.003

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.003 - Spearphishing via Service|T1566.003: Spearphishing via Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has used LinkedIn to send spearphishing links.(Citation: FireEye APT34 July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3d6abc5-11da-4d0c-a699-8cafac03dfab`.
