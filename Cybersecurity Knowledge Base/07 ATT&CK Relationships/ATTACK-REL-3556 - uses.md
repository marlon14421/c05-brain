---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "T1016.001"
stix_relationship_id: "relationship--8d557d2a-6d39-491f-bafc-c256910a59a2"
---
# Relationship 3556: G0030 — uses → T1016.001

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016.001 - Internet Connection Discovery|T1016.001: Internet Connection Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has performed checks to determine if a victim machine is able to access the Internet.(Citation: Cisco LotusBlossom 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d557d2a-6d39-491f-bafc-c256910a59a2`.
