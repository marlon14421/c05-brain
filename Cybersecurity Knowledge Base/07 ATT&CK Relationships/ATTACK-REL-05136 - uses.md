---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0082"
target_object: "T1189"
stix_relationship_id: "relationship--2d27c0d9-7e8e-4713-b3e1-0d82db27ac9a"
---
# Relationship 5136: G0082 — uses → T1189

**Source object:** [[01 ATT&CK/G0082 - APT38|G0082: APT38]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT38](https://attack.mitre.org/groups/G0082) has conducted watering holes schemes to gain initial access to victims.(Citation: FireEye APT38 Oct 2018)(Citation: CISA AA20-239A BeagleBoyz August 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d27c0d9-7e8e-4713-b3e1-0d82db27ac9a`.
