---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0098"
target_object: "T1124"
stix_relationship_id: "relationship--0d2a66c5-fb8e-4cbb-9526-579b5c9c881c"
---
# Relationship 4371: S0098 — uses → T1124

**Source object:** [[01 ATT&CK/S0098 - T9000|S0098: T9000]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[T9000](https://attack.mitre.org/software/S0098) gathers and beacons the system time during installation.(Citation: Palo Alto T9000 Feb 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d2a66c5-fb8e-4cbb-9526-579b5c9c881c`.
