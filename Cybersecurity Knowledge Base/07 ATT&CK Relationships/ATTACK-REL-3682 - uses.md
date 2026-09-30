---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0119"
target_object: "T1021.004"
stix_relationship_id: "relationship--f43de92c-7a30-4d24-82d1-4537d4fc3fb2"
---
# Relationship 3682: G0119 — uses → T1021.004

**Source object:** [[01 ATT&CK/G0119 - Indrik Spider|G0119: Indrik Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.004 - SSH|T1021.004: SSH]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Indrik Spider](https://attack.mitre.org/groups/G0119) has used SSH for lateral movement.(Citation: Mandiant_UNC2165)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f43de92c-7a30-4d24-82d1-4537d4fc3fb2`.
