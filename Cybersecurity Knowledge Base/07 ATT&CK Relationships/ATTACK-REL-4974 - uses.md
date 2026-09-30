---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1081"
target_object: "T1124"
stix_relationship_id: "relationship--39f8de6f-9df3-4e6b-9076-bd3464a2d5d2"
---
# Relationship 4974: S1081 — uses → T1124

**Source object:** [[01 ATT&CK/S1081 - BADHATCH|S1081: BADHATCH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BADHATCH](https://attack.mitre.org/software/S1081) can obtain the `DATETIME` and `UPTIME` from a compromised machine.(Citation: BitDefender BADHATCH Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39f8de6f-9df3-4e6b-9076-bd3464a2d5d2`.
