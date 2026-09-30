---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1031"
target_object: "T1132.001"
stix_relationship_id: "relationship--5ef73661-0bc8-47f5-bae6-2beb5342a68e"
---
# Relationship 3715: S1031 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1031 - PingPull|S1031: PingPull]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PingPull](https://attack.mitre.org/software/S1031) can encode C2 traffic with Base64.(Citation: Unit 42 PingPull Jun 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ef73661-0bc8-47f5-bae6-2beb5342a68e`.
