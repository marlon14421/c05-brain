---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1053.005"
stix_relationship_id: "relationship--e916bd35-cd90-4c1f-b600-aedffbf4de3c"
---
# Relationship 9646: S0650 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) has the ability to create scheduled tasks for persistence.(Citation: Trend Micro Qakbot May 2020)(Citation: Kroll Qakbot June 2020)(Citation: Crowdstrike Qakbot October 2020)(Citation: Trend Micro Qakbot December 2020)(Citation: Red Canary Qbot)(Citation: Cyberint Qakbot May 2021)(Citation: Kaspersky QakBot September 2021)(Citation: Group IB Ransomware September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e916bd35-cd90-4c1f-b600-aedffbf4de3c`.
