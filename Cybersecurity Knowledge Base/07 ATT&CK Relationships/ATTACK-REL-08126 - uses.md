---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1172"
target_object: "T1105"
stix_relationship_id: "relationship--9dbe8924-bf0a-4b76-98ff-04f6f442ae8b"
---
# Relationship 8126: S1172 — uses → T1105

**Source object:** [[01 ATT&CK/S1172 - OilBooster|S1172: OilBooster]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilBooster](https://attack.mitre.org/software/S1172) can download and execute files from an actor-controlled OneDrive account.(Citation: ESET OilRig Downloaders DEC 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9dbe8924-bf0a-4b76-98ff-04f6f442ae8b`.
