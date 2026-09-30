---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1152"
target_object: "T1053.005"
stix_relationship_id: "relationship--f4f8ff63-55bb-46ca-82ee-606302b2d455"
---
# Relationship 4075: S1152 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1152 - IMAPLoader|S1152: IMAPLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IMAPLoader](https://attack.mitre.org/software/S1152) creates scheduled tasks for persistence based on the operating system version of the victim machine.(Citation: PWC Yellow Liderc 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4f8ff63-55bb-46ca-82ee-606302b2d455`.
