---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1139"
target_object: "T1680"
stix_relationship_id: "relationship--68f0f623-b5f2-47a8-8206-eabfb472d7aa"
---
# Relationship 6600: S1139 — uses → T1680

**Source object:** [[01 ATT&CK/S1139 - INC Ransomware|S1139: INC Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransomware](https://attack.mitre.org/software/S1139) can discover and mount hidden drives to encrypt them.(Citation: Cybereason INC Ransomware November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68f0f623-b5f2-47a8-8206-eabfb472d7aa`.
