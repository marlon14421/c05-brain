---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1106"
stix_relationship_id: "relationship--96f5cb23-3dc4-4690-b745-914e85b0c95e"
---
# Relationship 3159: G0094 — uses → T1106

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has utilized Native APIs to collect data from victim hosts and facilitate execution of malicious scripts.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)(Citation: Aryaka Kimsuky July 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96f5cb23-3dc4-4690-b745-914e85b0c95e`.
