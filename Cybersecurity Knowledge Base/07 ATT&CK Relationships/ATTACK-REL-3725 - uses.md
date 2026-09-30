---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "S1155"
stix_relationship_id: "relationship--6f917518-2f54-479e-a008-cbf6bd6037c0"
---
# Relationship 3725: G0125 — uses → S1155

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1155 - Covenant|S1155: Covenant]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HAFNIUM](https://attack.mitre.org/groups/G0125) used [Covenant](https://attack.mitre.org/software/S1155) for command and control following compromise of internet-facing servers.(Citation: Microsoft HAFNIUM March 2020)(Citation: Microsoft Silk Typhoon MAR 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6f917518-2f54-479e-a008-cbf6bd6037c0`.
