---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9026"
target_object: "T1480"
stix_relationship_id: "relationship--90a3bf9a-3edd-4a86-ab53-6fda02c6d375"
---
# Relationship 3940: S9026 — uses → T1480

**Source object:** [[01 ATT&CK/S9026 - ROAMINGHOUSE|S9026: ROAMINGHOUSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ROAMINGHOUSE](https://attack.mitre.org/software/S9026) can change its execution method to create a batch file in the startup folder that executes a legitimate executable if a McAfee product is detected.(Citation: Trend Micro Earth Kasha Updates APR 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90a3bf9a-3edd-4a86-ab53-6fda02c6d375`.
