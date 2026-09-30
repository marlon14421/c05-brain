---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0410"
target_object: "T1132.001"
stix_relationship_id: "relationship--0edefa7f-0b1b-48b7-ab51-e0107b48c683"
---
# Relationship 4383: S0410 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0410 - Fysbis|S0410: Fysbis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Fysbis](https://attack.mitre.org/software/S0410) can use Base64 to encode its C2 traffic.(Citation: Fysbis Dr Web Analysis)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0edefa7f-0b1b-48b7-ab51-e0107b48c683`.
