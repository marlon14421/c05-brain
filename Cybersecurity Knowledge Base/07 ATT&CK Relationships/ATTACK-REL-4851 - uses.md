---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1497.001"
stix_relationship_id: "relationship--05d8ec5a-0fc4-4037-913f-4d48e658ee9b"
---
# Relationship 4851: S0650 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) can check the compromised host for the presence of multiple executables associated with analysis tools and halt execution if any are found.(Citation: Trend Micro Qakbot May 2020)(Citation: ATT QakBot April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05d8ec5a-0fc4-4037-913f-4d48e658ee9b`.
