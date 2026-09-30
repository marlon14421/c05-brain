---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1011"
target_object: "T1102"
stix_relationship_id: "relationship--9094f15c-c60c-4366-8c1b-22f21e1156b8"
---
# Relationship 7512: G1011 — uses → T1102

**Source object:** [[01 ATT&CK/G1011 - EXOTIC LILY|G1011: EXOTIC LILY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has used file-sharing services including WeTransfer, TransferNow, and OneDrive to deliver payloads.(Citation: Google EXOTIC LILY March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9094f15c-c60c-4366-8c1b-22f21e1156b8`.
