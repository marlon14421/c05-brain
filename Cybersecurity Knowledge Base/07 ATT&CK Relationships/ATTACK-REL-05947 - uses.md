---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1071.001"
stix_relationship_id: "relationship--5d5a903f-d71f-42d5-941b-154d2e06ca78"
---
# Relationship 5947: S0650 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) has the ability to use HTTP and HTTPS in communication with C2 servers.(Citation: Trend Micro Qakbot May 2020)(Citation: Crowdstrike Qakbot October 2020)(Citation: Kaspersky QakBot September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d5a903f-d71f-42d5-941b-154d2e06ca78`.
