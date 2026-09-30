---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1059.005"
stix_relationship_id: "relationship--d50a6bf2-266b-4770-809a-c1bf3e81305f"
---
# Relationship 5514: S0650 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) can use VBS to download and execute malicious files.(Citation: Trend Micro Qakbot May 2020) (Citation: Kroll Qakbot June 2020)(Citation: Crowdstrike Qakbot October 2020)(Citation: Trend Micro Qakbot December 2020)(Citation: Cyberint Qakbot May 2021)(Citation: Group IB Ransomware September 2020)(Citation: Trend Micro Black Basta October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d50a6bf2-266b-4770-809a-c1bf3e81305f`.
