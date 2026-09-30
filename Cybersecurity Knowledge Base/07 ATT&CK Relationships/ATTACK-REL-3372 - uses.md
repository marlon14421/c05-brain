---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1140"
target_object: "T1036.004"
stix_relationship_id: "relationship--c11054b6-8e97-483d-b941-44dd723184f6"
---
# Relationship 3372: S1140 — uses → T1036.004

**Source object:** [[01 ATT&CK/S1140 - Spica|S1140: Spica]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Spica](https://attack.mitre.org/software/S1140) has created a scheduled task named `CalendarChecker` for persistence on compromised hosts.(Citation: Google TAG COLDRIVER January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c11054b6-8e97-483d-b941-44dd723184f6`.
