---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1059.003"
stix_relationship_id: "relationship--12362fa5-736b-4cac-9d74-51cd559f1e7c"
---
# Relationship 6638: S0650 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) can use cmd.exe to launch itself and to execute multiple C2 commands.(Citation: Crowdstrike Qakbot October 2020)(Citation: ATT QakBot April 2021)(Citation: Kaspersky QakBot September 2021)(Citation: Trend Micro Black Basta October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--12362fa5-736b-4cac-9d74-51cd559f1e7c`.
