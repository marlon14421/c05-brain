---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0497"
target_object: "T1543.001"
stix_relationship_id: "relationship--4c391d8f-4db1-43b3-857e-b8c507f27bdb"
---
# Relationship 4679: S0497 — uses → T1543.001

**Source object:** [[01 ATT&CK/S0497 - Dacls|S0497: Dacls]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dacls](https://attack.mitre.org/software/S0497) can establish persistence via a LaunchAgent.(Citation: SentinelOne Lazarus macOS July 2020)(Citation: TrendMicro macOS Dacls May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c391d8f-4db1-43b3-857e-b8c507f27bdb`.
