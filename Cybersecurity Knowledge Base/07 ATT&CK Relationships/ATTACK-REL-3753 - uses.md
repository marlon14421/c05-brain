---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1037"
target_object: "T1204.001"
stix_relationship_id: "relationship--dc7ab03a-ba08-4a79-9b5d-c0c38aa14577"
---
# Relationship 3753: G1037 — uses → T1204.001

**Source object:** [[01 ATT&CK/G1037 - TA577|G1037: TA577]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA577](https://attack.mitre.org/groups/G1037) has lured users into executing malicious JavaScript files by sending malicious links via email.(Citation: Latrodectus APR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc7ab03a-ba08-4a79-9b5d-c0c38aa14577`.
