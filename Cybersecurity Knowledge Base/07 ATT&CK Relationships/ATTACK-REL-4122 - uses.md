---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0004"
target_object: "T1685"
stix_relationship_id: "relationship--2f132e5d-680c-4394-b4c7-c808cc3aadf6"
---
# Relationship 4122: S0004 — uses → T1685

**Source object:** [[01 ATT&CK/S0004 - TinyZBot|S0004: TinyZBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TinyZBot](https://attack.mitre.org/software/S0004) can disable Avira anti-virus.(Citation: Cylance Cleaver)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f132e5d-680c-4394-b4c7-c808cc3aadf6`.
