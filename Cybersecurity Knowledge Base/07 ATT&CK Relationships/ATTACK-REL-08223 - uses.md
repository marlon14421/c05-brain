---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0051"
target_object: "T1016.002"
stix_relationship_id: "relationship--3a9465fb-9a28-47d1-aec1-f62dc30de566"
---
# Relationship 8223: C0051 — uses → T1016.002

**Source object:** [[01 ATT&CK/C0051 - APT28 Nearest Neighbor Campaign|C0051: APT28 Nearest Neighbor Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016.002 - Wi-Fi Discovery|T1016.002: Wi-Fi Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [APT28 Nearest Neighbor Campaign](https://attack.mitre.org/campaigns/C0051), [APT28](https://attack.mitre.org/groups/G0007) collected information on wireless interfaces within range of a compromised system.(Citation: Nearest Neighbor Volexity)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a9465fb-9a28-47d1-aec1-f62dc30de566`.
