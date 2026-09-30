---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1505.003"
stix_relationship_id: "relationship--cde53969-2e25-4424-b840-fe42806ee64e"
---
# Relationship 4388: G1051 — uses → T1505.003

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has utilized webshells to an exploited Microsoft Exchange Server.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cde53969-2e25-4424-b840-fe42806ee64e`.
