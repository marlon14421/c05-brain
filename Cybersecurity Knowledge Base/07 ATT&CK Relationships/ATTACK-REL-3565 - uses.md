---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0530"
target_object: "T1027.002"
stix_relationship_id: "relationship--c90424e7-4d58-4b2f-b72e-fc630a1a8199"
---
# Relationship 3565: S0530 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0530 - Melcoz|S0530: Melcoz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Melcoz](https://attack.mitre.org/software/S0530) has been packed with VMProtect and Themida.(Citation: Securelist Brazilian Banking Malware July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c90424e7-4d58-4b2f-b72e-fc630a1a8199`.
