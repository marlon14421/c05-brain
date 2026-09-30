---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0260"
target_object: "T1057"
stix_relationship_id: "relationship--eb1c808f-5806-4169-bd41-6ea7c7f17ffb"
---
# Relationship 3073: S0260 — uses → T1057

**Source object:** [[01 ATT&CK/S0260 - InvisiMole|S0260: InvisiMole]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[InvisiMole](https://attack.mitre.org/software/S0260) can obtain a list of running processes.(Citation: ESET InvisiMole June 2018)(Citation: ESET InvisiMole June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb1c808f-5806-4169-bd41-6ea7c7f17ffb`.
