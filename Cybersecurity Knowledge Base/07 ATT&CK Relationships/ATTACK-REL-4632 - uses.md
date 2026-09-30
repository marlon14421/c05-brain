---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0532"
target_object: "T1498"
stix_relationship_id: "relationship--bb19637b-a68f-48fd-8b14-41607f32888d"
---
# Relationship 4632: S0532 — uses → T1498

**Source object:** [[01 ATT&CK/S0532 - Lucifer|S0532: Lucifer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1498 - Network Denial of Service|T1498: Network Denial of Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lucifer](https://attack.mitre.org/software/S0532) can execute TCP, UDP, and HTTP denial of service (DoS) attacks.(Citation: Unit 42 Lucifer June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb19637b-a68f-48fd-8b14-41607f32888d`.
