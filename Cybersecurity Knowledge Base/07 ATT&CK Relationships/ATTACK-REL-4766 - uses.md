---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1564.003"
stix_relationship_id: "relationship--ce0e4e49-3c40-4bce-96bd-460df4cb2124"
---
# Relationship 4766: G0094 — uses → T1564.003

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used an information gathering module that will hide an AV software window from the victim.(Citation: Talos Kimsuky Nov 2021) [Kimsuky](https://attack.mitre.org/groups/G0094) has also been known to use `-WindowStyle Hidden` to conceal PowerShell windows.(Citation: Securonix Kimsuky February 2025)(Citation: Aryaka Kimsuky July 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce0e4e49-3c40-4bce-96bd-460df4cb2124`.
