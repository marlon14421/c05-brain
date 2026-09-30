---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0046"
target_object: "S1186"
stix_relationship_id: "relationship--19b6ad5a-3a22-434f-a04c-a49fa2c0f307"
---
# Relationship 4792: C0046 — uses → S1186

**Source object:** [[01 ATT&CK/C0046 - ArcaneDoor|C0046: ArcaneDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1186 - Line Dancer|S1186: Line Dancer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Line Dancer](https://attack.mitre.org/software/S1186) is uniquely associated with the [ArcaneDoor](https://attack.mitre.org/campaigns/C0046) campaign.(Citation: CCCS ArcaneDoor 2024)(Citation: Cisco ArcaneDoor 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19b6ad5a-3a22-434f-a04c-a49fa2c0f307`.
