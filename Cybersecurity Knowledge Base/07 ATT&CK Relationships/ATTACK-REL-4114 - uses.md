---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1529"
stix_relationship_id: "relationship--394fe21a-c7a6-4571-abf5-03377b934634"
---
# Relationship 4114: S9042 — uses → T1529

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has forced the target system to reboot after file deletion.(Citation: Aikido CanisterWorm MAR 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--394fe21a-c7a6-4571-abf5-03377b934634`.
