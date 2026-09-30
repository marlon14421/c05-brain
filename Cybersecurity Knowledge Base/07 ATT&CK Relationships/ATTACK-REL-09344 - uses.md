---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "T1592.004"
stix_relationship_id: "relationship--02c3ea88-c33c-47d8-a34a-532ed5498a3d"
---
# Relationship 9344: G0125 — uses → T1592.004

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1592.004 - Client Configurations|T1592.004: Client Configurations]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HAFNIUM](https://attack.mitre.org/groups/G0125) has interacted with Office 365 tenants to gather details regarding target's environments.(Citation: Microsoft HAFNIUM March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02c3ea88-c33c-47d8-a34a-532ed5498a3d`.
