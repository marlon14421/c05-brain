---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1588.004"
stix_relationship_id: "relationship--74cd7fa0-af3f-4f50-ba66-b479b57f8a74"
---
# Relationship 5181: G0129 — uses → T1588.004

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.004 - Digital Certificates|T1588.004: Digital Certificates]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has obtained SSL certificates for their C2 domains.(Citation: EclecticIQ Mustang Panda PlugX)(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74cd7fa0-af3f-4f50-ba66-b479b57f8a74`.
