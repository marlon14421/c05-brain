---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1152"
target_object: "T1082"
stix_relationship_id: "relationship--778df1e8-d307-496d-861a-45052ee2e019"
---
# Relationship 3280: S1152 — uses → T1082

**Source object:** [[01 ATT&CK/S1152 - IMAPLoader|S1152: IMAPLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IMAPLoader](https://attack.mitre.org/software/S1152) uses WMI queries to gather information about the victim machine.(Citation: PWC Yellow Liderc 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--778df1e8-d307-496d-861a-45052ee2e019`.
