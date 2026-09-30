---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1014"
target_object: "T1204.002"
stix_relationship_id: "relationship--57c8dc86-93a0-43d6-a47c-f0f5892948b3"
---
# Relationship 4249: S1014 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1014 - DanBot|S1014: DanBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DanBot](https://attack.mitre.org/software/S1014) has relied on victims' opening a malicious file for initial execution.(Citation: SecureWorks August 2019)(Citation: ClearSky Siamesekitten August 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--57c8dc86-93a0-43d6-a47c-f0f5892948b3`.
