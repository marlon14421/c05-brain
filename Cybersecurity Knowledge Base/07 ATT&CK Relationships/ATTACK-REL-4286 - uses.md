---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1132"
target_object: "T1070"
stix_relationship_id: "relationship--038940df-ae44-4ca6-a417-6e4aac6a2f56"
---
# Relationship 4286: S1132 — uses → T1070

**Source object:** [[01 ATT&CK/S1132 - IPsec Helper|S1132: IPsec Helper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IPsec Helper](https://attack.mitre.org/software/S1132) can delete various registry keys related to its execution and use.(Citation: SentinelOne Agrius 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--038940df-ae44-4ca6-a417-6e4aac6a2f56`.
