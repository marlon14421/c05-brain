---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1033"
target_object: "T1204.002"
stix_relationship_id: "relationship--4e7d7d9e-c3d5-4a9d-a948-d50724932321"
---
# Relationship 2885: G1033 — uses → T1204.002

**Source object:** [[01 ATT&CK/G1033 - Star Blizzard|G1033: Star Blizzard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Star Blizzard](https://attack.mitre.org/groups/G1033) has lured targets into opening malicious .pdf files to deliver malware.(Citation: Google TAG COLDRIVER January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e7d7d9e-c3d5-4a9d-a948-d50724932321`.
