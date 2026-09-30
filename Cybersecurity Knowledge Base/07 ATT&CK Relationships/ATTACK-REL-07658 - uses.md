---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1139"
target_object: "T1486"
stix_relationship_id: "relationship--7d8dcd8d-3ca4-4464-b8ab-9dee24f93c70"
---
# Relationship 7658: S1139 — uses → T1486

**Source object:** [[01 ATT&CK/S1139 - INC Ransomware|S1139: INC Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransomware](https://attack.mitre.org/software/S1139) can encrypt data on victim systems, including through the use of partial encryption and multi-threading to speed encryption.(Citation: SentinelOne INC Ransomware)(Citation: Huntress INC Ransom Group August 2023)(Citation: Cybereason INC Ransomware November 2023)(Citation: SOCRadar INC Ransom January 2024)(Citation: SentinelOne INC Ransomware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d8dcd8d-3ca4-4464-b8ab-9dee24f93c70`.
