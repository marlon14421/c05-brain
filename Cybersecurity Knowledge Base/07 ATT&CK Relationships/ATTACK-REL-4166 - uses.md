---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0114"
target_object: "T1564.005"
stix_relationship_id: "relationship--29a6afc7-f051-4c26-b6a2-cad09c73180f"
---
# Relationship 4166: S0114 — uses → T1564.005

**Source object:** [[01 ATT&CK/S0114 - BOOTRASH|S0114: BOOTRASH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.005 - Hidden File System|T1564.005: Hidden File System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BOOTRASH](https://attack.mitre.org/software/S0114) has used unallocated disk space between partitions for a hidden file system that stores components of the Nemesis bootkit.(Citation: FireEye Bootkits)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29a6afc7-f051-4c26-b6a2-cad09c73180f`.
