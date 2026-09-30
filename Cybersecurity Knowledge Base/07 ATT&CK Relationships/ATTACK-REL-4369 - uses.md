---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1039"
target_object: "T1204.001"
stix_relationship_id: "relationship--c4600507-03d9-471f-a175-d5fd3953c0c6"
---
# Relationship 4369: S1039 — uses → T1204.001

**Source object:** [[01 ATT&CK/S1039 - Bumblebee|S1039: Bumblebee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bumblebee](https://attack.mitre.org/software/S1039) has relied upon a user downloading a file from a OneDrive link for execution.(Citation: Proofpoint Bumblebee April 2022)(Citation: Cybereason Bumblebee August 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4600507-03d9-471f-a175-d5fd3953c0c6`.
