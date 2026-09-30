---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0567"
target_object: "T1056.001"
stix_relationship_id: "relationship--28bde4e9-cc84-4356-a872-b18fc3dd49ab"
---
# Relationship 4559: S0567 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0567 - Dtrack|S0567: Dtrack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dtrack](https://attack.mitre.org/software/S0567)’s dropper contains a keylogging executable.(Citation: Securelist Dtrack)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--28bde4e9-cc84-4356-a872-b18fc3dd49ab`.
