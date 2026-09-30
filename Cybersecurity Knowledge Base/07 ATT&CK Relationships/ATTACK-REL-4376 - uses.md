---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0073"
target_object: "T1204.002"
stix_relationship_id: "relationship--b033e131-e448-46c6-815b-b86e4bd6d638"
---
# Relationship 4376: G0073 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0073 - APT19|G0073: APT19]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT19](https://attack.mitre.org/groups/G0073) attempted to get users to launch malicious attachments delivered via spearphishing emails.(Citation: FireEye APT19)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b033e131-e448-46c6-815b-b86e4bd6d638`.
