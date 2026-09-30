---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0175"
target_object: "T1090.004"
stix_relationship_id: "relationship--b1334535-019a-4d6a-88c1-8bb6741f152b"
---
# Relationship 7225: S0175 — uses → T1090.004

**Source object:** [[01 ATT&CK/S0175 - meek|S0175: meek]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.004 - Domain Fronting|T1090.004: Domain Fronting]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[meek](https://attack.mitre.org/software/S0175) uses Domain Fronting to disguise the destination of network traffic as another server that is hosted in the same Content Delivery Network (CDN) as the intended destination.

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1334535-019a-4d6a-88c1-8bb6741f152b`.
