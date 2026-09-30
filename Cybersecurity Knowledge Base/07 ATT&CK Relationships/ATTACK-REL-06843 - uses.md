---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1550.001"
stix_relationship_id: "relationship--1af6f63b-b54b-496a-a85f-dbedf2f79b9c"
---
# Relationship 6843: G1057 — uses → T1550.001

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550.001 - Application Access Token|T1550.001: Application Access Token]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has used stolen OAuth keys to access cloud infrastructure and to bypass two-factor authentication.(Citation: Intel471_SH_Aug2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1af6f63b-b54b-496a-a85f-dbedf2f79b9c`.
