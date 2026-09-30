---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1053"
target_object: "T1529"
stix_relationship_id: "relationship--fc89b538-26d8-434a-954f-e7d0b384b506"
---
# Relationship 2655: S1053 — uses → T1529

**Source object:** [[01 ATT&CK/S1053 - AvosLocker|S1053: AvosLocker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AvosLocker](https://attack.mitre.org/software/S1053)’s Linux variant has terminated ESXi virtual machines.(Citation: Trend Micro AvosLocker Apr 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc89b538-26d8-434a-954f-e7d0b384b506`.
