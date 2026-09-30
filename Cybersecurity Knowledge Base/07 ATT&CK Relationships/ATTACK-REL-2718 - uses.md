---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1044"
target_object: "T1056"
stix_relationship_id: "relationship--37f4170b-b4ea-470b-8ee6-ff15ba35d472"
---
# Relationship 2718: G1044 — uses → T1056

**Source object:** [[01 ATT&CK/G1044 - APT42|G1044: APT42]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056 - Input Capture|T1056: Input Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT42](https://attack.mitre.org/groups/G1044) has used credential harvesting websites.(Citation: Mandiant APT42-untangling)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--37f4170b-b4ea-470b-8ee6-ff15ba35d472`.
