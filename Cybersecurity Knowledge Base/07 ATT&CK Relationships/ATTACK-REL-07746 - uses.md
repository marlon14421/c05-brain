---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1518.001"
stix_relationship_id: "relationship--1343df30-b011-42f7-b3a3-a5d1d2f0b9c6"
---
# Relationship 7746: S0650 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) can identify the installed antivirus product on a targeted system.(Citation: Crowdstrike Qakbot October 2020)(Citation: ATT QakBot April 2021)(Citation: ATT QakBot April 2021)(Citation: Kaspersky QakBot September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1343df30-b011-42f7-b3a3-a5d1d2f0b9c6`.
