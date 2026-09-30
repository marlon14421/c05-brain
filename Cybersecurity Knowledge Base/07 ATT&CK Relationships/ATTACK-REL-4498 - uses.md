---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1038"
target_object: "T1594"
stix_relationship_id: "relationship--c2308f9a-8564-4e10-bdab-d22c4be590db"
---
# Relationship 4498: G1038 — uses → T1594

**Source object:** [[01 ATT&CK/G1038 - TA578|G1038: TA578]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1594 - Search Victim-Owned Websites|T1594: Search Victim-Owned Websites]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA578](https://attack.mitre.org/groups/G1038) has filled out contact forms on victims' websites to direct them to adversary-controlled URLs.(Citation: Latrodectus APR 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2308f9a-8564-4e10-bdab-d22c4be590db`.
