---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1039"
target_object: "T1080"
stix_relationship_id: "relationship--29282003-9cf6-4cdf-b87d-92dfcf2b1d52"
---
# Relationship 5426: G1039 — uses → T1080

**Source object:** [[01 ATT&CK/G1039 - RedCurl|G1039: RedCurl]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1080 - Taint Shared Content|T1080: Taint Shared Content]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedCurl](https://attack.mitre.org/groups/G1039) has placed modified LNK files on network drives for lateral movement.(Citation: group-ib_redcurl1)(Citation: group-ib_redcurl2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29282003-9cf6-4cdf-b87d-92dfcf2b1d52`.
