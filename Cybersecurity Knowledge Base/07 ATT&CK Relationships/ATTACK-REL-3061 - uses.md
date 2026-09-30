---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0428"
target_object: "T1082"
stix_relationship_id: "relationship--77d954c5-de84-4f4b-98b6-5ad35603ae7a"
---
# Relationship 3061: S0428 — uses → T1082

**Source object:** [[01 ATT&CK/S0428 - PoetRAT|S0428: PoetRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PoetRAT](https://attack.mitre.org/software/S0428) has the ability to gather information about the compromised host.(Citation: Talos PoetRAT April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77d954c5-de84-4f4b-98b6-5ad35603ae7a`.
