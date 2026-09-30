---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1009"
target_object: "T1016"
stix_relationship_id: "relationship--209d5669-2e7e-4621-905a-f22ba07f06d6"
---
# Relationship 3810: G1009 — uses → T1016

**Source object:** [[01 ATT&CK/G1009 - Moses Staff|G1009: Moses Staff]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Moses Staff](https://attack.mitre.org/groups/G1009) has collected the domain name of a compromised network.(Citation: Checkpoint MosesStaff Nov 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--209d5669-2e7e-4621-905a-f22ba07f06d6`.
