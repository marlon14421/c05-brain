---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0659"
target_object: "T1018"
stix_relationship_id: "relationship--afe9286d-076f-49af-90f3-11ebbe82ad40"
---
# Relationship 3618: S0659 — uses → T1018

**Source object:** [[01 ATT&CK/S0659 - Diavol|S0659: Diavol]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Diavol](https://attack.mitre.org/software/S0659) can use the ARP table to find remote hosts to scan.(Citation: Fortinet Diavol July 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--afe9286d-076f-49af-90f3-11ebbe82ad40`.
