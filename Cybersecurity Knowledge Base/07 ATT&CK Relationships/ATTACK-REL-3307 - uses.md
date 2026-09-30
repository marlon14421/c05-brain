---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1218.011"
stix_relationship_id: "relationship--ea33531e-7a8f-45a1-a408-c8f405512aaa"
---
# Relationship 3307: S0650 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) has used Rundll32.exe to drop malicious DLLs including [Brute Ratel C4](https://attack.mitre.org/software/S1063) and to enable C2 communication.(Citation: Crowdstrike Qakbot October 2020)(Citation: Red Canary Qbot)(Citation: Cyberint Qakbot May 2021)(Citation: ATT QakBot April 2021)(Citation: Trend Micro Black Basta October 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea33531e-7a8f-45a1-a408-c8f405512aaa`.
