---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1213.005"
stix_relationship_id: "relationship--bf341c57-1bdf-4d7a-8c01-1d94acce69a8"
---
# Relationship 6961: G1015 — uses → T1213.005

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1213.005 - Messaging Applications|T1213.005: Messaging Applications]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) threat actors search the victim’s Slack and Microsoft Teams for conversations about the intrusion and incident response.(Citation: CISA Scattered Spider Advisory November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf341c57-1bdf-4d7a-8c01-1d94acce69a8`.
