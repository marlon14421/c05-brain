---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1027"
target_object: "T1204.002"
stix_relationship_id: "relationship--f56f129e-0a30-4be0-bc4b-5942a479e0f9"
---
# Relationship 2927: S1027 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1027 - Heyoka Backdoor|S1027: Heyoka Backdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Heyoka Backdoor](https://attack.mitre.org/software/S1027) has been spread through malicious document lures.(Citation: SentinelOne Aoqin Dragon June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f56f129e-0a30-4be0-bc4b-5942a479e0f9`.
