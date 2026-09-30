---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0374"
target_object: "T1046"
stix_relationship_id: "relationship--467f79d6-edf7-4e6a-a0d7-8196cd406ce1"
---
# Relationship 4372: S0374 — uses → T1046

**Source object:** [[01 ATT&CK/S0374 - SpeakUp|S0374: SpeakUp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SpeakUp](https://attack.mitre.org/software/S0374) checks for availability of specific ports on servers.(Citation: CheckPoint SpeakUp Feb 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--467f79d6-edf7-4e6a-a0d7-8196cd406ce1`.
