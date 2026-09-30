---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "T1003.003"
stix_relationship_id: "relationship--94175b7b-a332-4e38-9d7b-3b900825bb3a"
---
# Relationship 4983: C0029 — uses → T1003.003

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Cutting Edge](https://attack.mitre.org/campaigns/C0029), threat actors accessed and mounted virtual hard disk backups to extract ntds.dit.(Citation: Volexity Ivanti Zero-Day Exploitation January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94175b7b-a332-4e38-9d7b-3b900825bb3a`.
