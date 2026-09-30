---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0019"
target_object: "T1018"
stix_relationship_id: "relationship--2794f341-b46f-482c-b5b7-2cc7c2dcadb5"
---
# Relationship 4181: G0019 — uses → T1018

**Source object:** [[01 ATT&CK/G0019 - Naikon|G0019: Naikon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Naikon](https://attack.mitre.org/groups/G0019) has used a netbios scanner for remote machine identification.(Citation: Bitdefender Naikon April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2794f341-b46f-482c-b5b7-2cc7c2dcadb5`.
