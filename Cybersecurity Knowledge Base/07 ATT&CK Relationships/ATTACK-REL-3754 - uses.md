---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0452"
target_object: "T1018"
stix_relationship_id: "relationship--15a571d1-652c-4148-9dee-12d3b1cbff62"
---
# Relationship 3754: S0452 — uses → T1018

**Source object:** [[01 ATT&CK/S0452 - USBferry|S0452: USBferry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[USBferry](https://attack.mitre.org/software/S0452) can use net view to gather information about remote systems.(Citation: TrendMicro Tropic Trooper May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15a571d1-652c-4148-9dee-12d3b1cbff62`.
