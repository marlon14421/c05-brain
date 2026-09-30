---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0393"
target_object: "T1057"
stix_relationship_id: "relationship--772089d3-b06e-4e5e-993b-1351f71484e7"
---
# Relationship 4257: S0393 — uses → T1057

**Source object:** [[01 ATT&CK/S0393 - PowerStallion|S0393: PowerStallion]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PowerStallion](https://attack.mitre.org/software/S0393) has been used to monitor process lists.(Citation: ESET Turla PowerShell May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--772089d3-b06e-4e5e-993b-1351f71484e7`.
