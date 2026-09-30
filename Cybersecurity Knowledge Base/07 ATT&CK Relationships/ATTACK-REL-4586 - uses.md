---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0064"
target_object: "S0039"
stix_relationship_id: "relationship--d22af09f-5536-4416-827c-e401cfae3002"
---
# Relationship 4586: G0064 — uses → S0039

**Source object:** [[01 ATT&CK/G0064 - APT33|G0064: APT33]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0039 - Net|S0039: Net]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Symantec Elfin Mar 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d22af09f-5536-4416-827c-e401cfae3002`.
