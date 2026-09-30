---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0373"
target_object: "T1129"
stix_relationship_id: "relationship--30c9343b-bb15-494a-a1cf-4449131ec216"
---
# Relationship 4398: S0373 — uses → T1129

**Source object:** [[01 ATT&CK/S0373 - Astaroth|S0373: Astaroth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Astaroth](https://attack.mitre.org/software/S0373) uses the LoadLibraryExW() function to load additional modules. (Citation: Cybereason Astaroth Feb 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30c9343b-bb15-494a-a1cf-4449131ec216`.
