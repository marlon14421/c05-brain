---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0610"
target_object: "T1005"
stix_relationship_id: "relationship--9fb48ae2-125f-48f8-a813-8e64cf70bde3"
---
# Relationship 8617: S0610 — uses → T1005

**Source object:** [[01 ATT&CK/S0610 - SideTwist|S0610: SideTwist]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SideTwist](https://attack.mitre.org/software/S0610) has the ability to upload files from a compromised host.(Citation: Check Point APT34 April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9fb48ae2-125f-48f8-a813-8e64cf70bde3`.
