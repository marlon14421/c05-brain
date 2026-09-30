---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0357"
target_object: "T1570"
stix_relationship_id: "relationship--b58c89b5-cade-4622-b0bc-5d9a921afc60"
---
# Relationship 4646: S0357 — uses → T1570

**Source object:** [[01 ATT&CK/S0357 - Impacket|S0357: Impacket]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Impacket](https://attack.mitre.org/software/S0357) has used its `wmiexec` command, leveraging Windows Management Instrumentation, to remotely stage and execute payloads in victim networks.(Citation: Sygnia VelvetAnt 2024A)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b58c89b5-cade-4622-b0bc-5d9a921afc60`.
