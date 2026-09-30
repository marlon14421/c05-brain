---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1012"
target_object: "T1585.001"
stix_relationship_id: "relationship--6fc8e3dd-1bb7-4e76-8a8c-9e836f944488"
---
# Relationship 8297: G1012 — uses → T1585.001

**Source object:** [[01 ATT&CK/G1012 - CURIUM|G1012: CURIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.001 - Social Media Accounts|T1585.001: Social Media Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CURIUM](https://attack.mitre.org/groups/G1012) has established a network of fictitious social media accounts, including on Facebook and LinkedIn, to establish relationships with victims, often posing as an attractive woman.(Citation: Microsoft Iranian Threat Actor Trends November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6fc8e3dd-1bb7-4e76-8a8c-9e836f944488`.
