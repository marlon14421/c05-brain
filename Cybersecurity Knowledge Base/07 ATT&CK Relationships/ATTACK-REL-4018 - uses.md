---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1149"
target_object: "T1059.005"
stix_relationship_id: "relationship--0cd688c6-1e0b-4004-b4fd-bbfb79478dd4"
---
# Relationship 4018: S1149 — uses → T1059.005

**Source object:** [[01 ATT&CK/S1149 - CHIMNEYSWEEP|S1149: CHIMNEYSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CHIMNEYSWEEP](https://attack.mitre.org/software/S1149) has executed a script named cln.vbs on compromised hosts.(Citation: Mandiant ROADSWEEP August 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cd688c6-1e0b-4004-b4fd-bbfb79478dd4`.
