---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1185"
target_object: "T1071.001"
stix_relationship_id: "relationship--5a0a5102-e52f-4766-be1b-6b9142aee8e9"
---
# Relationship 2806: S1185 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1185 - LightSpy|S1185: LightSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LightSpy](https://attack.mitre.org/software/S1185)'s C2 communication is performed over WebSockets using the open source library SocketRocket with functionality such as, heartbeat, receiving commands, and updating command status.(Citation: Huntress LightSpy macOS 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a0a5102-e52f-4766-be1b-6b9142aee8e9`.
