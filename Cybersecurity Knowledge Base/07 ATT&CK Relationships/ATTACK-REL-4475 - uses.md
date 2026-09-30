---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1069"
stix_relationship_id: "relationship--166836f7-8e31-4b80-bcab-61382bc79ad0"
---
# Relationship 4475: G0096 — uses → T1069

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069 - Permission Groups Discovery|T1069: Permission Groups Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) used net group commands to enumerate various Windows user groups and permissions.(Citation: Rostovcev APT41 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--166836f7-8e31-4b80-bcab-61382bc79ad0`.
