---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0032"
target_object: "T1057"
stix_relationship_id: "relationship--a564f3da-349a-4e65-826c-8ca60bc920bf"
---
# Relationship 4871: S0032 — uses → T1057

**Source object:** [[01 ATT&CK/S0032 - gh0st RAT|S0032: gh0st RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[gh0st RAT](https://attack.mitre.org/software/S0032) has the capability to list processes.(Citation: FireEye Hacking Team)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a564f3da-349a-4e65-826c-8ca60bc920bf`.
