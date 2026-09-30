---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1186"
target_object: "T1082"
stix_relationship_id: "relationship--e452a193-b1a0-40b6-af3e-a734859fcf0b"
---
# Relationship 4060: S1186 — uses → T1082

**Source object:** [[01 ATT&CK/S1186 - Line Dancer|S1186: Line Dancer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Line Dancer](https://attack.mitre.org/software/S1186) can gather system configuration information by running the native `show configuration` command.(Citation: Cisco ArcaneDoor 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e452a193-b1a0-40b6-af3e-a734859fcf0b`.
