---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0547"
target_object: "T1614.001"
stix_relationship_id: "relationship--b0b2abea-e4a0-4e96-8e71-9ff49b4759f7"
---
# Relationship 4126: S0547 — uses → T1614.001

**Source object:** [[01 ATT&CK/S0547 - DropBook|S0547: DropBook]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DropBook](https://attack.mitre.org/software/S0547) has checked for the presence of Arabic language in the infected machine's settings.(Citation: BleepingComputer Molerats Dec 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0b2abea-e4a0-4e96-8e71-9ff49b4759f7`.
