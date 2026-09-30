---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0056"
target_object: "G1048"
stix_relationship_id: "relationship--3cde6cab-a70e-45d3-b1e5-a7a6ba08241e"
---
# Relationship 2623: C0056 — attributed-to → G1048

**Source object:** [[01 ATT&CK/C0056 - RedPenguin|C0056: RedPenguin]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

In mid-2024 Mandiant identified custom TINYSHELL-based backdoors deployed on Juniper Networks’ Junos OS routers. Mandiant attributed these backdoors to the China-nexus espionage group [UNC3886](https://attack.mitre.org/groups/G1048).(Citation: Mandiant UNC3886 Juniper Routers MAR 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cde6cab-a70e-45d3-b1e5-a7a6ba08241e`.
