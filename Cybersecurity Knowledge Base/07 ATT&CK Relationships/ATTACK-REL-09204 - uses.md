---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1189"
target_object: "T1095"
stix_relationship_id: "relationship--337835d7-bd03-48ae-bb34-9cf85ffbd4e4"
---
# Relationship 9204: S1189 — uses → T1095

**Source object:** [[01 ATT&CK/S1189 - Neo-reGeorg|S1189: Neo-reGeorg]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Neo-reGeorg](https://attack.mitre.org/software/S1189) can create multiple TCP connections for a single session.(Citation: GitHub Neo-reGeorg 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--337835d7-bd03-48ae-bb34-9cf85ffbd4e4`.
