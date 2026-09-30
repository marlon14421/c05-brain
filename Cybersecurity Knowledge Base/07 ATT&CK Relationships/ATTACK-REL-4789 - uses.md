---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0081"
target_object: "T1082"
stix_relationship_id: "relationship--cd5799f3-8be5-4272-88db-626940136130"
---
# Relationship 4789: G0081 — uses → T1082

**Source object:** [[01 ATT&CK/G0081 - Tropic Trooper|G0081: Tropic Trooper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Tropic Trooper](https://attack.mitre.org/groups/G0081) has detected a target system’s OS version.(Citation: TrendMicro TropicTrooper 2015)(Citation: TrendMicro Tropic Trooper May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd5799f3-8be5-4272-88db-626940136130`.
