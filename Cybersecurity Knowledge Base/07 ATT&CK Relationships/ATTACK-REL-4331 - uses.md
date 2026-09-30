---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0079"
target_object: "T1187"
stix_relationship_id: "relationship--2db02b07-4dd3-4810-9103-1f8d7bd46a60"
---
# Relationship 4331: G0079 — uses → T1187

**Source object:** [[01 ATT&CK/G0079 - DarkHydrus|G0079: DarkHydrus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1187 - Forced Authentication|T1187: Forced Authentication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkHydrus](https://attack.mitre.org/groups/G0079) used [Template Injection](https://attack.mitre.org/techniques/T1221) to launch an authentication window for users to enter their credentials.(Citation: Unit 42 Phishery Aug 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2db02b07-4dd3-4810-9103-1f8d7bd46a60`.
