---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1147"
target_object: "T1053.005"
stix_relationship_id: "relationship--3781213b-225b-4c18-bfb6-f69d622887f6"
---
# Relationship 3490: S1147 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1147 - Nightdoor|S1147: Nightdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Nightdoor](https://attack.mitre.org/software/S1147) uses scheduled tasks for persistence to load the final malware payload into memory.(Citation: Symantec Daggerfly 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3781213b-225b-4c18-bfb6-f69d622887f6`.
