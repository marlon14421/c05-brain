---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1032"
target_object: "T1219"
stix_relationship_id: "relationship--78601356-fa8e-47f5-b5ad-01549bac169f"
---
# Relationship 7851: G1032 — uses → T1219

**Source object:** [[01 ATT&CK/G1032 - INC Ransom|G1032: INC Ransom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219 - Remote Access Tools|T1219: Remote Access Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransom](https://attack.mitre.org/groups/G1032) has used AnyDesk and PuTTY on compromised systems.(Citation: Huntress INC Ransom Group August 2023)(Citation: SOCRadar INC Ransom January 2024)(Citation: Huntress INC Ransomware May 2024)(Citation: SentinelOne INC Ransomware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--78601356-fa8e-47f5-b5ad-01549bac169f`.
