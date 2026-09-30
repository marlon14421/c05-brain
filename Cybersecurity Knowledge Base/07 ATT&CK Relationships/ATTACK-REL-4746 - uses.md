---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1039"
target_object: "T1039"
stix_relationship_id: "relationship--1fe3ccfb-2ed1-412f-af7e-c63821a5e434"
---
# Relationship 4746: G1039 — uses → T1039

**Source object:** [[01 ATT&CK/G1039 - RedCurl|G1039: RedCurl]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1039 - Data from Network Shared Drive|T1039: Data from Network Shared Drive]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RedCurl](https://attack.mitre.org/groups/G1039) has collected data about network drives.(Citation: group-ib_redcurl1)(Citation: group-ib_redcurl2)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1fe3ccfb-2ed1-412f-af7e-c63821a5e434`.
