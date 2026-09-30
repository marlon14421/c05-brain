---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1539"
stix_relationship_id: "relationship--7f92fc3c-044c-4095-be4b-f6482a5619d1"
---
# Relationship 4895: S0650 — uses → T1539

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1539 - Steal Web Session Cookie|T1539: Steal Web Session Cookie]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) has the ability to capture web session cookies.(Citation: Kroll Qakbot June 2020)(Citation: Kaspersky QakBot September 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7f92fc3c-044c-4095-be4b-f6482a5619d1`.
