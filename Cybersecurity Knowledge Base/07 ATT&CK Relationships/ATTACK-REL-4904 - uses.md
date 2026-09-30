---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1064"
target_object: "T1124"
stix_relationship_id: "relationship--9414386b-adbf-4117-ba5b-81a242714d83"
---
# Relationship 4904: S1064 — uses → T1124

**Source object:** [[01 ATT&CK/S1064 - SVCReady|S1064: SVCReady]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SVCReady](https://attack.mitre.org/software/S1064) can collect time zone information.(Citation: HP SVCReady Jun 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9414386b-adbf-4117-ba5b-81a242714d83`.
