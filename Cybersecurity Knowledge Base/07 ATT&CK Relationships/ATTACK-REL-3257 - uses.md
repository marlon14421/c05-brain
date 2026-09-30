---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0625"
target_object: "T1134"
stix_relationship_id: "relationship--c280ba3f-7210-4608-b895-d29932938fe7"
---
# Relationship 3257: S0625 — uses → T1134

**Source object:** [[01 ATT&CK/S0625 - Cuba|S0625: Cuba]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cuba](https://attack.mitre.org/software/S0625) has used SeDebugPrivilege and AdjustTokenPrivileges to elevate privileges.(Citation: McAfee Cuba April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c280ba3f-7210-4608-b895-d29932938fe7`.
