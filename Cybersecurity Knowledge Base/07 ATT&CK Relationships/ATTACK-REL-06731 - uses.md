---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1584.001"
stix_relationship_id: "relationship--134cc6c4-30f8-4b85-8ea1-da19c3e92af9"
---
# Relationship 6731: G0059 — uses → T1584.001

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.001 - Domains|T1584.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) has used compromised domains to host links targeted to specific phishing victims.(Citation: ClearSky Kittens Back 3 August 2020)(Citation: Proofpoint TA453 July2021)(Citation: Certfa Charming Kitten January 2021)(Citation: Google Iran Threats October 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--134cc6c4-30f8-4b85-8ea1-da19c3e92af9`.
