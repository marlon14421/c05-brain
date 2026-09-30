---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1561.002"
stix_relationship_id: "relationship--8b331f1e-76b5-47a9-81b4-118083a54198"
---
# Relationship 2778: G1055 — uses → T1561.002

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.002 - Disk Structure Wipe|T1561.002: Disk Structure Wipe]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has deployed custom wipers that overwrite system files and the host devices master boot records (MBR) to corrupt or destroy files.(Citation: Check Point VOID MANTICORE Handala Hack March 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b331f1e-76b5-47a9-81b4-118083a54198`.
