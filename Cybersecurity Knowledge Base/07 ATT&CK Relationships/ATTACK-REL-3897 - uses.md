---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0216"
target_object: "T1189"
stix_relationship_id: "relationship--f32828b5-ab55-4bf5-af89-1d6e42d559b0"
---
# Relationship 3897: S0216 — uses → T1189

**Source object:** [[01 ATT&CK/S0216 - POORAIM|S0216: POORAIM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[POORAIM](https://attack.mitre.org/software/S0216) has been delivered through compromised sites acting as watering holes.(Citation: FireEye APT37 Feb 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f32828b5-ab55-4bf5-af89-1d6e42d559b0`.
