---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0344"
target_object: "T1552.001"
stix_relationship_id: "relationship--3e418cf0-fbe4-4de1-84bf-e137c5c0a72a"
---
# Relationship 3439: S0344 — uses → T1552.001

**Source object:** [[01 ATT&CK/S0344 - Azorult|S0344: Azorult]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Azorult](https://attack.mitre.org/software/S0344) can steal credentials in files belonging to common software such as Skype, Telegram, and Steam.(Citation: Unit42 Azorult Nov 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e418cf0-fbe4-4de1-84bf-e137c5c0a72a`.
