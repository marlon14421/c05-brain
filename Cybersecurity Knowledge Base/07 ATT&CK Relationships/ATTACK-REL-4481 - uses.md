---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0647"
target_object: "T1059.006"
stix_relationship_id: "relationship--a7d7b40a-aae7-4fbc-a1c9-f6c7b756c4dd"
---
# Relationship 4481: S0647 — uses → T1059.006

**Source object:** [[01 ATT&CK/S0647 - Turian|S0647: Turian]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Turian](https://attack.mitre.org/software/S0647) has the ability to use Python to spawn a Unix shell.(Citation: ESET BackdoorDiplomacy Jun 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7d7b40a-aae7-4fbc-a1c9-f6c7b756c4dd`.
