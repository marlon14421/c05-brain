---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0538"
target_object: "T1560.001"
stix_relationship_id: "relationship--01202a82-56cc-4770-abf1-1a37c8717dba"
---
# Relationship 3467: S0538 — uses → T1560.001

**Source object:** [[01 ATT&CK/S0538 - Crutch|S0538: Crutch]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Crutch](https://attack.mitre.org/software/S0538) has used the WinRAR utility to compress and encrypt stolen files.(Citation: ESET Crutch December 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--01202a82-56cc-4770-abf1-1a37c8717dba`.
