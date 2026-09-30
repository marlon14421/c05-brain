---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1199"
target_object: "T1685.005"
stix_relationship_id: "relationship--8bfd8a04-63b1-4c2f-a6ba-adc67ab87154"
---
# Relationship 4720: S1199 — uses → T1685.005

**Source object:** [[01 ATT&CK/S1199 - LockBit 2.0|S1199: LockBit 2.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.005 - Clear Windows Event Logs|T1685.005: Clear Windows Event Logs]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LockBit 2.0](https://attack.mitre.org/software/S1199) can delete log files through the use of wevtutil.(Citation: FBI Lockbit 2.0 FEB 2022)(Citation: Palo Alto Lockbit 2.0 JUN 2022)(Citation: Cybereason Lockbit 2.0)(Citation: SentinelOne LockBit 2.0)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8bfd8a04-63b1-4c2f-a6ba-adc67ab87154`.
