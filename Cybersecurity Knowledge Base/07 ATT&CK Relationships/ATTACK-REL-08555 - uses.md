---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0056"
target_object: "T1587.003"
stix_relationship_id: "relationship--66e5238f-c1f7-4094-8c2e-e8e41a4c12f3"
---
# Relationship 8555: G0056 — uses → T1587.003

**Source object:** [[01 ATT&CK/G0056 - PROMETHIUM|G0056: PROMETHIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.003 - Digital Certificates|T1587.003: Digital Certificates]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PROMETHIUM](https://attack.mitre.org/groups/G0056) has created self-signed digital certificates for use in HTTPS C2 traffic.(Citation: Talos Promethium June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66e5238f-c1f7-4094-8c2e-e8e41a4c12f3`.
