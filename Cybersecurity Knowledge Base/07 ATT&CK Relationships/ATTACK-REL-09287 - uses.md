---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1589"
stix_relationship_id: "relationship--d0946a00-610b-44d3-aec6-be292cfac52a"
---
# Relationship 9287: G0059 — uses → T1589

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1589 - Gather Victim Identity Information|T1589: Gather Victim Identity Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) has acquired mobile phone numbers of potential targets, possibly for mobile malware or additional phishing operations.(Citation: Proofpoint TA453 July2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0946a00-610b-44d3-aec6-be292cfac52a`.
