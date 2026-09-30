---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0601"
target_object: "T1552.005"
stix_relationship_id: "relationship--ced41648-7201-4eb8-aaae-c376e05af519"
---
# Relationship 3281: S0601 — uses → T1552.005

**Source object:** [[01 ATT&CK/S0601 - Hildegard|S0601: Hildegard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.005 - Cloud Instance Metadata API|T1552.005: Cloud Instance Metadata API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Hildegard](https://attack.mitre.org/software/S0601) has queried the Cloud Instance Metadata API for cloud credentials.(Citation: Unit 42 Hildegard Malware)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ced41648-7201-4eb8-aaae-c376e05af519`.
