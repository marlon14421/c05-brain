---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1087"
target_object: "T1564.003"
stix_relationship_id: "relationship--783f71a1-8a2b-4dbe-9011-a24042f36c88"
---
# Relationship 3711: S1087 — uses → T1564.003

**Source object:** [[01 ATT&CK/S1087 - AsyncRAT|S1087: AsyncRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AsyncRAT](https://attack.mitre.org/software/S1087) can hide the execution of scheduled tasks using `ProcessWindowStyle.Hidden`.(Citation: Telefonica Snip3 December 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--783f71a1-8a2b-4dbe-9011-a24042f36c88`.
