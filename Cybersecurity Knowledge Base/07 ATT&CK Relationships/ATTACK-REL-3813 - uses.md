---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1572"
stix_relationship_id: "relationship--ea904c7f-f3a7-4e47-884f-bc13e38b09c6"
---
# Relationship 3813: S0650 — uses → T1572

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [QakBot](https://attack.mitre.org/software/S0650) proxy module can encapsulate SOCKS5 protocol within its own proxy protocol.(Citation: Kaspersky QakBot September 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea904c7f-f3a7-4e47-884f-bc13e38b09c6`.
