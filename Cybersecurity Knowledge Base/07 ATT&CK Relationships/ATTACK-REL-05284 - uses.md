---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1192"
target_object: "T1105"
stix_relationship_id: "relationship--f3e042f4-e641-4d7e-8c8d-40d17851eeda"
---
# Relationship 5284: S1192 — uses → T1105

**Source object:** [[01 ATT&CK/S1192 - NICECURL|S1192: NICECURL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NICECURL](https://attack.mitre.org/software/S1192) has the ability to download additional content onto an infected machine, e.g. by using `curl`.(Citation: Mandiant APT42-untangling)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f3e042f4-e641-4d7e-8c8d-40d17851eeda`.
