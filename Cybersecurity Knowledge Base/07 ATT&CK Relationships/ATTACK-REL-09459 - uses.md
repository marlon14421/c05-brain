---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0473"
target_object: "T1105"
stix_relationship_id: "relationship--96c91811-fec3-43a6-890f-08921e543325"
---
# Relationship 9459: S0473 — uses → T1105

**Source object:** [[01 ATT&CK/S0473 - Avenger|S0473: Avenger]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Avenger](https://attack.mitre.org/software/S0473) has the ability to download files from C2 to a compromised host.(Citation: Trend Micro Tick November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96c91811-fec3-43a6-890f-08921e543325`.
