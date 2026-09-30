---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0459"
target_object: "T1132.001"
stix_relationship_id: "relationship--553dc864-7d6b-41f9-bb1c-9fc6ee3724b7"
---
# Relationship 2663: S0459 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0459 - MechaFlounder|S0459: MechaFlounder]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MechaFlounder](https://attack.mitre.org/software/S0459) has the ability to use base16 encoded strings in C2.(Citation: Unit 42 MechaFlounder March 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--553dc864-7d6b-41f9-bb1c-9fc6ee3724b7`.
