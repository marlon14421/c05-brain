---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0057"
target_object: "T1102.001"
stix_relationship_id: "relationship--75daf0b5-2ad5-4950-a895-ec7a34de330b"
---
# Relationship 2812: C0057 — uses → T1102.001

**Source object:** [[01 ATT&CK/C0057 - 3CX Supply Chain Attack|C0057: 3CX Supply Chain Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.001 - Dead Drop Resolver|T1102.001: Dead Drop Resolver]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [3CX Supply Chain Attack](https://attack.mitre.org/campaigns/C0057), [AppleJeus](https://attack.mitre.org/groups/G1049) leveraged a GitHub repository to host icon files containing the command and control URL.(Citation: Unit42 3cx supply chain 2023)(Citation: Mandiant 3cx UNC4736 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75daf0b5-2ad5-4950-a895-ec7a34de330b`.
