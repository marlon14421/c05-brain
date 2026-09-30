---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0461"
target_object: "T1105"
stix_relationship_id: "relationship--7ef04aca-4890-4035-8c0b-69d9a78e8029"
---
# Relationship 6834: S0461 — uses → T1105

**Source object:** [[01 ATT&CK/S0461 - SDBbot|S0461: SDBbot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SDBbot](https://attack.mitre.org/software/S0461) has the ability to download a DLL from C2 to a compromised host.(Citation: Proofpoint TA505 October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ef04aca-4890-4035-8c0b-69d9a78e8029`.
