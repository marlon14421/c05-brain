---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1091"
target_object: "T1526"
stix_relationship_id: "relationship--7a980213-1df8-481f-af86-ed105781c573"
---
# Relationship 8240: S1091 — uses → T1526

**Source object:** [[01 ATT&CK/S1091 - Pacu|S1091: Pacu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1526 - Cloud Service Discovery|T1526: Cloud Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pacu](https://attack.mitre.org/software/S1091) can enumerate AWS services, such as CloudTrail and CloudWatch.(Citation: GitHub Pacu)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a980213-1df8-481f-af86-ed105781c573`.
