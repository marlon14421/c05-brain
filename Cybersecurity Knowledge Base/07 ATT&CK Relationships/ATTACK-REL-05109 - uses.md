---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1039"
target_object: "T1114.001"
stix_relationship_id: "relationship--1c54cdd2-576a-4ba5-9cf2-33bda233e018"
---
# Relationship 5109: G1039 — uses → T1114.001

**Source object:** [[01 ATT&CK/G1039 - RedCurl|G1039: RedCurl]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114.001 - Local Email Collection|T1114.001: Local Email Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedCurl](https://attack.mitre.org/groups/G1039) has collected emails to use in future phishing campaigns.(Citation: group-ib_redcurl1)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c54cdd2-576a-4ba5-9cf2-33bda233e018`.
