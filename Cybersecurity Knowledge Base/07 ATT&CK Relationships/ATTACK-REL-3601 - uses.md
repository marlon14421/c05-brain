---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "T1505.003"
stix_relationship_id: "relationship--4224f857-32f1-4288-959c-f4dca6a826dd"
---
# Relationship 3601: G1030 — uses → T1505.003

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Agrius](https://attack.mitre.org/groups/G1030) typically deploys a variant of the [ASPXSpy](https://attack.mitre.org/software/S0073) web shell following initial access via exploitation.(Citation: SentinelOne Agrius 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4224f857-32f1-4288-959c-f4dca6a826dd`.
