---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0112"
target_object: "S0466"
stix_relationship_id: "relationship--4fb841dd-93d8-404a-8738-5fe19a53c730"
---
# Relationship 4390: G0112 — uses → S0466

**Source object:** [[01 ATT&CK/G0112 - Windshift|G0112: Windshift]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0466 - WindTail|S0466: WindTail]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: SANS Windshift August 2018)(Citation: objective-see windtail1 dec 2018)(Citation: objective-see windtail2 jan 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4fb841dd-93d8-404a-8738-5fe19a53c730`.
