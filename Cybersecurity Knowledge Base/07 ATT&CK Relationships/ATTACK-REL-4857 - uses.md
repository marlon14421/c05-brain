---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0396"
target_object: "T1070.004"
stix_relationship_id: "relationship--ad3eb54c-0f67-42b8-b4cf-060ab6057b79"
---
# Relationship 4857: S0396 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0396 - EvilBunny|S0396: EvilBunny]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[EvilBunny](https://attack.mitre.org/software/S0396) has deleted the initial dropper after running through the environment checks.(Citation: Cyphort EvilBunny Dec 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad3eb54c-0f67-42b8-b4cf-060ab6057b79`.
