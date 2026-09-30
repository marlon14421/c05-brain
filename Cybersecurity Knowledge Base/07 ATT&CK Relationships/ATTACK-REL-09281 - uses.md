---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0257"
target_object: "T1105"
stix_relationship_id: "relationship--d68649d8-4f18-48b8-93b8-82c8660fc464"
---
# Relationship 9281: S0257 — uses → T1105

**Source object:** [[01 ATT&CK/S0257 - VERMIN|S0257: VERMIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VERMIN](https://attack.mitre.org/software/S0257) can download and upload files to the victim's machine.(Citation: Unit 42 VERMIN Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d68649d8-4f18-48b8-93b8-82c8660fc464`.
