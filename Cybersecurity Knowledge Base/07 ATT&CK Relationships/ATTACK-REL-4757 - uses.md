---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1152"
target_object: "T1047"
stix_relationship_id: "relationship--344e4ab0-d480-4d70-b64d-539cf5f26c96"
---
# Relationship 4757: S1152 — uses → T1047

**Source object:** [[01 ATT&CK/S1152 - IMAPLoader|S1152: IMAPLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IMAPLoader](https://attack.mitre.org/software/S1152) uses WMI queries to query system information on victim hosts.(Citation: PWC Yellow Liderc 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--344e4ab0-d480-4d70-b64d-539cf5f26c96`.
