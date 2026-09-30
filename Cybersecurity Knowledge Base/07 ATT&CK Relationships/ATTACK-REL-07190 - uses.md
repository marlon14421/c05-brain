---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1244"
target_object: "T1518.001"
stix_relationship_id: "relationship--1c792ece-e1d9-4819-9621-1b704a23839d"
---
# Relationship 7190: S1244 — uses → T1518.001

**Source object:** [[01 ATT&CK/S1244 - Medusa Ransomware|S1244: Medusa Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Ransomware](https://attack.mitre.org/software/S1244) has the capability to detect security solutions for termination or deletion within the victim device using hard-coded lists of strings containing security product executables.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c792ece-e1d9-4819-9621-1b704a23839d`.
