---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1148"
target_object: "T1105"
stix_relationship_id: "relationship--688a4ea0-c9ff-4bb1-a6ab-fc565cea1461"
---
# Relationship 5815: S1148 — uses → T1105

**Source object:** [[01 ATT&CK/S1148 - Raccoon Stealer|S1148: Raccoon Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raccoon Stealer](https://attack.mitre.org/software/S1148) downloads various library files enabling interaction with various data stores and structures to facilitate follow-on information theft.(Citation: S2W Racoon 2022)(Citation: Sekoia Raccoon2 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--688a4ea0-c9ff-4bb1-a6ab-fc565cea1461`.
