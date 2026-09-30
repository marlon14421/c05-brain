---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1039"
target_object: "T1548.002"
stix_relationship_id: "relationship--b8113737-894f-42de-b607-9d4905fcdfc3"
---
# Relationship 3165: S1039 — uses → T1548.002

**Source object:** [[01 ATT&CK/S1039 - Bumblebee|S1039: Bumblebee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1548.002 - Bypass User Account Control|T1548.002: Bypass User Account Control]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bumblebee](https://attack.mitre.org/software/S1039) has the ability to bypass UAC to deploy post exploitation tools with elevated privileges.(Citation: Cybereason Bumblebee August 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b8113737-894f-42de-b607-9d4905fcdfc3`.
