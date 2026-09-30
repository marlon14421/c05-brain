---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1044"
target_object: "T1566.002"
stix_relationship_id: "relationship--f565693e-80f4-40a8-8f28-f1a9bd0d1918"
---
# Relationship 2827: G1044 — uses → T1566.002

**Source object:** [[01 ATT&CK/G1044 - APT42|G1044: APT42]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT42](https://attack.mitre.org/groups/G1044) has sent spearphishing emails containing malicious links.(Citation: Mandiant APT42-charms)(Citation: Mandiant APT42-untangling)(Citation: TAG APT42)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f565693e-80f4-40a8-8f28-f1a9bd0d1918`.
