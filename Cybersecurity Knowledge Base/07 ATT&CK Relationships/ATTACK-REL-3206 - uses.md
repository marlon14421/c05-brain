---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0678"
target_object: "T1124"
stix_relationship_id: "relationship--1a192f9a-d515-4d5c-9c52-e904bac96f61"
---
# Relationship 3206: S0678 — uses → T1124

**Source object:** [[01 ATT&CK/S0678 - Torisma|S0678: Torisma]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Torisma](https://attack.mitre.org/software/S0678) can collect the current time on a victim machine.(Citation: McAfee Lazarus Nov 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a192f9a-d515-4d5c-9c52-e904bac96f61`.
