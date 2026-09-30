---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1013"
target_object: "T1057"
stix_relationship_id: "relationship--13a3b832-a680-4c50-b413-c8137a6a89b5"
---
# Relationship 3425: S1013 — uses → T1057

**Source object:** [[01 ATT&CK/S1013 - ZxxZ|S1013: ZxxZ]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZxxZ](https://attack.mitre.org/software/S1013) has created a snapshot of running processes using `CreateToolhelp32Snapshot`.(Citation: Cisco Talos Bitter Bangladesh May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13a3b832-a680-4c50-b413-c8137a6a89b5`.
