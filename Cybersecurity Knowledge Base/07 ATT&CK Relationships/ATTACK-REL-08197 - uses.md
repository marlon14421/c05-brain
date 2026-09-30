---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1082"
stix_relationship_id: "relationship--d5be9ea1-7bf2-453b-bbca-19a9d82ea532"
---
# Relationship 8197: S0650 — uses → T1082

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) can collect system information including the OS version and domain on a compromised host.(Citation: Crowdstrike Qakbot October 2020)(Citation: ATT QakBot April 2021)(Citation: Group IB Ransomware September 2020)(Citation: Microsoft Ransomware as a Service)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5be9ea1-7bf2-453b-bbca-19a9d82ea532`.
