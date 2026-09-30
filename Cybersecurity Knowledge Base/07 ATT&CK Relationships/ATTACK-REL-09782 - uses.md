---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9021"
target_object: "T1105"
stix_relationship_id: "relationship--526929a7-d746-477b-a34b-fe41e2e2e16a"
---
# Relationship 9782: S9021 — uses → T1105

**Source object:** [[01 ATT&CK/S9021 - DOWNIISSA|S9021: DOWNIISSA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DOWNIISSA](https://attack.mitre.org/software/S9021) can download files to the compromised host.(Citation: Kaspersky LODEINFO OCT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--526929a7-d746-477b-a34b-fe41e2e2e16a`.
