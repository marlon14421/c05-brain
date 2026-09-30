---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1139"
target_object: "T1135"
stix_relationship_id: "relationship--6c62f14a-0c1a-4dea-82eb-8c352d0c5f70"
---
# Relationship 7975: S1139 — uses → T1135

**Source object:** [[01 ATT&CK/S1139 - INC Ransomware|S1139: INC Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransomware](https://attack.mitre.org/software/S1139) has the ability to check for shared network drives to encrypt.(Citation: Cybereason INC Ransomware November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c62f14a-0c1a-4dea-82eb-8c352d0c5f70`.
