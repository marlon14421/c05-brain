---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1217"
target_object: "T1036.004"
stix_relationship_id: "relationship--ae3397ba-a9b1-45d3-a102-db21dab54f18"
---
# Relationship 9066: S1217 — uses → T1036.004

**Source object:** [[01 ATT&CK/S1217 - VIRTUALPITA|S1217: VIRTUALPITA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VIRTUALPITA](https://attack.mitre.org/software/S1217) has utilized VMware service names and ports to masquerade as legitimate services.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae3397ba-a9b1-45d3-a102-db21dab54f18`.
