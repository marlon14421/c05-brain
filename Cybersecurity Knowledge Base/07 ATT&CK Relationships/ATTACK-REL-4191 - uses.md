---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0039"
target_object: "T1201"
stix_relationship_id: "relationship--0224ebf5-13ef-4fb0-b9e7-53ea58c15a4d"
---
# Relationship 4191: S0039 — uses → T1201

**Source object:** [[01 ATT&CK/S0039 - Net|S0039: Net]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1201 - Password Policy Discovery|T1201: Password Policy Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The net accounts and net accounts /domain commands with [Net](https://attack.mitre.org/software/S0039) can be used to obtain password policy information.(Citation: Savill 1999)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0224ebf5-13ef-4fb0-b9e7-53ea58c15a4d`.
