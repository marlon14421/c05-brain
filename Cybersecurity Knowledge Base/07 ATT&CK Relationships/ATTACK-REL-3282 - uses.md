---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1038"
target_object: "T1059.007"
stix_relationship_id: "relationship--e81d7554-faad-40a2-99dd-75183efa712c"
---
# Relationship 3282: G1038 — uses → T1059.007

**Source object:** [[01 ATT&CK/G1038 - TA578|G1038: TA578]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA578](https://attack.mitre.org/groups/G1038) has used JavaScript files in malware execution chains.(Citation: Latrodectus APR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e81d7554-faad-40a2-99dd-75183efa712c`.
