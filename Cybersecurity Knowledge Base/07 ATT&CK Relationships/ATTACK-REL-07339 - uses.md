---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1068"
target_object: "T1486"
stix_relationship_id: "relationship--29cec373-a87c-444b-b192-9ab94f69a008"
---
# Relationship 7339: S1068 — uses → T1486

**Source object:** [[01 ATT&CK/S1068 - BlackCat|S1068: BlackCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackCat](https://attack.mitre.org/software/S1068) has the ability to encrypt Windows devices, Linux devices, and VMWare instances.(Citation: Microsoft BlackCat Jun 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29cec373-a87c-444b-b192-9ab94f69a008`.
