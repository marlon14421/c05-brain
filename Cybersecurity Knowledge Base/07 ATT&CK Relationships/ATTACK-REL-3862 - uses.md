---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1043"
target_object: "T1016"
stix_relationship_id: "relationship--0c6913d6-f4a4-49cc-8458-cd876c429865"
---
# Relationship 3862: G1043 — uses → T1016

**Source object:** [[01 ATT&CK/G1043 - BlackByte|G1043: BlackByte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackByte](https://attack.mitre.org/groups/G1043) used tools such as [Arp](https://attack.mitre.org/software/S0099) to pull system network information and identify connected devices.(Citation: FBI BlackByte 2022)(Citation: Microsoft BlackByte 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c6913d6-f4a4-49cc-8458-cd876c429865`.
