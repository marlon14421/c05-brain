---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0134"
target_object: "T1564.001"
stix_relationship_id: "relationship--88f1dfcb-3b2a-494d-bab2-027602c4f78f"
---
# Relationship 2867: G0134 — uses → T1564.001

**Source object:** [[01 ATT&CK/G0134 - Transparent Tribe|G0134: Transparent Tribe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Transparent Tribe](https://attack.mitre.org/groups/G0134) can hide legitimate directories and replace them with malicious copies of the same name.(Citation: Kaspersky Transparent Tribe August 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88f1dfcb-3b2a-494d-bab2-027602c4f78f`.
